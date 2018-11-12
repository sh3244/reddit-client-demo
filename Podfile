# Uncomment the next line to define a global platform for your project
platform :ios, '11.0'

project 'Reddit Client Demo.xcodeproj'
workspace 'Reddit Client Demo.xcworkspace'

def shared_pods
    pod 'FLEX', '2.0', :configurations => ['Debug']

    pod 'SteviaLayout', '4.3.0'

    # Promises
    pod 'PromiseKit', '4.5.2'

    # Device detection
    pod 'DeviceKit', '1.4.0'

    # JSON parser
    pod 'SwiftyJSON', '4.0.0'

    # Networking
    pod 'Alamofire', '4.7.1'
    pod 'AlamofireObjectMapper', '5.0.0'

    # Analytics
    # pod 'Analytics', '3.6.9'
    # pod 'Segment-Mixpanel', '1.3.0'

    # Logging
    pod 'KeychainAccess', '3.1.0'

    # LCS diff calculator
    pod 'Dwifft', '0.8'

    pod 'Crashlytics', '3.9.3'
    pod 'Fabric', '1.7.6'
end

target 'Reddit Client Demo' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Reddit Client Demo
  shared_pods

  target 'Reddit Client DemoTests' do
    inherit! :search_paths
    # Pods for testing

    pod 'Quick', '1.2.0'
    pod 'Nimble', '7.0.3'
  end

end

#post_install do | installer |
#    `patch -p0 < Diffs/ReverseExtension.diff`
#    installer.pods_project.targets.each do |target|
#        if target.name == "ReverseExtension"
#            target.build_configurations.each do |config|
#                config.build_settings['SWIFT_INSTALL_OBJC_HEADER'] = 'NO'
#            end
#        end
#    end
#end
