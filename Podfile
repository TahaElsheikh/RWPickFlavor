platform :ios, '8.0'
use_frameworks!

target 'RWPickFlavor' do
pod 'Alamofire', '~> 4.4'
pod 'MBProgressHUD', '~> 0.9.0'
end
post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['SWIFT_VERSION'] = '2.0'
    end
  end
end