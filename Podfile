platform :ios, '13.0'

target 'Flash Chat iOS13' do
  use_frameworks!
  
  
  post_install do |pi|
  pi.pods_project.targets.each do |t|
  t.build_configurations.each do |config|
  config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '9.0'
  end
  end
  end
  

  # Pods for Flash Chat iOS13

    pod 'Firebase/Auth'
    pod 'Firebase/Firestore'
    pod 'IQKeyboardManagerSwift', '6.3.0'

end
