# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'


target 'InstagramClone' do
  pod 'Firebase/Core'
  pod 'Firebase/Messaging'
  pod 'Firebase/Database'
  pod 'Firebase/Storage'
  pod 'Firebase/Auth'
  pod 'Firebase/RemoteConfig'
  pod 'RSKImageCropper'
end

target 'InstagramCloneTests' do
    
end

target 'InstagramCloneUITests' do
    
end

post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['SWIFT_VERSION'] = '3.0'
        end
    end
end