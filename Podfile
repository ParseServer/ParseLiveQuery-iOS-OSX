use_frameworks!
workspace 'ParseLiveQuery.xcworkspace'

def commonPods
  pod 'Parse'
  pod 'Bolts-Swift'
  pod 'SocketRocket'
end

target 'ParseLiveQuery-OSX' do
  project 'Sources/ParseLiveQuery.xcodeproj'
  platform :osx, '10.9'

  commonPods
end

target 'ParseLiveQuery-iOS' do
  project 'Sources/ParseLiveQuery.xcodeproj'
  platform :ios, '8.0'

  commonPods
end

target 'LiveQueryDemo' do
  project 'Examples/LiveQueryDemo.xcodeproj'
  platform :osx, '10.9'

  commonPods
end

target 'LiveQueryDemo-ObjC' do
  project 'Examples/LiveQueryDemo-ObjC.xcodeproj'
  platform :osx, '10.9'

  commonPods
end
