# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

plugin "cocoapods-binary-cache"

target 'PodCacheSample' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
  
  pod 'AFNetworking', :binary => true
  pod 'SDWebImage', :binary => true
  pod 'Alamofire', :binary => true
  pod 'MBProgressHUD', :binary => true
  pod 'Masonry', :binary => true
  pod 'SwiftyJSON', :binary => true
  pod 'SVProgressHUD', :binary => true
  pod 'MJRefresh', :binary => true
  pod 'CocoaLumberjack', :binary => true
  pod 'SnapKit', :binary => true
  pod 'Kingfisher', :binary => true
  
  

  # Pods for PodCacheSample

  target 'PodCacheSampleTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'PodCacheSampleUITests' do
    # Pods for testing
  end
end

config_cocoapods_binary_cache(
  cache_repo: {
    "default" => {
      "remote" => "git@github.com:showcove/PodCacheRepo.git",
      "local" => "~/.cocoapods-binary-cache/prebuilt-frameworks"
    }
  }
)
