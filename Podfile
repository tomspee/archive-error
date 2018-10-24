def sharedPods
  pod 'Alamofire', '~> 4.5.0'
end

target 'TestProject' do
  platform :ios, '10.0'
  
  use_frameworks!

  sharedPods

  target 'TestProjectTests' do
    inherit! :search_paths

  end

  target 'TestProjectUITests' do
    inherit! :search_paths

  end

end

target 'Widget' do
  platform :ios, '12.0'
  
  use_frameworks!
  
  sharedPods
end
