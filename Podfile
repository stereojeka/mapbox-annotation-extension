platform :ios, '9.0'

def shared_pods
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
  pod 'Mapbox-iOS-SDK', '~> 6.0.0', git: => 'https://github.com/stereojeka/mapbox-gl-native-ios.git'
end

target 'MapboxAnnotationExtension' do
  shared_pods

  target 'MapboxAnnotationExtensionTests' do

  end

end

target 'annotationapp' do
  shared_pods
end
