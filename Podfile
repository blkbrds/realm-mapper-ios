source 'https://github.com/CocoaPods/Specs.git'
inhibit_all_warnings!
use_frameworks!
platform :ios, '8.0'

target 'RealmMapper' do  
    pod 'RealmSwift', '~> 1.0'
    pod 'ObjectMapper', '~> 1.2.0'
  
    target 'Tests' do
        inherit! :search_paths
        pod 'RealmSwift', '~> 1.0'
        pod 'ObjectMapper', '~> 1.2.0'
    end
end
