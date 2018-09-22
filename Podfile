# Uncomment the next line to define a global platform for your project
platform :ios, '9.0'

target 'testDemoApp' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for testDemoApp
  def testing_pods
    pod 'Quick'
    pod 'Nimble'
  end

  target 'testDemoAppTests' do
    inherit! :search_paths
    # Pods for testing
    testing_pods
  end

  target 'testDemoAppUITests' do
    inherit! :search_paths
    # Pods for testing
    testing_pods
  end

end
