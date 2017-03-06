use_frameworks!

platform :ios, '8.0'

target 'Endpoint' do
  pod 'Alamofire', '~> 3.5'
end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['SWIFT_VERSION'] = '2.3'
    end
  end
end
