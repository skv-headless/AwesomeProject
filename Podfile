# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'ExampleProject' do
  # Uncomment the next line if you're using Swift or would like to use dynamic frameworks
  # use_frameworks!

   pod 'React', :path => './node_modules/react-native', :subspecs => [
    'Core',
    'RCTText',
    'RCTNetwork',
    'RCTWebSocket', # needed for debugging
    'RCTAnimation',
    # Add any other subspecs you want to use in your project
  ]
  pod 'Yoga', :path => './node_modules/react-native/ReactCommon/yoga'

  target 'ExampleProjectTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'ExampleProjectUITests' do
    inherit! :search_paths
    # Pods for testing
  end

end
