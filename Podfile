use_frameworks!

source 'https://github.com/CocoaPods/Specs.git'
source 'https://github.com/LNOrganization/LNSpec.git'

platform :ios, '11.0'

target 'ArchitectureDesign' do
#
  pod 'LNAccountModule', '~>1.0.1'
  pod 'LNFeedModule', '~>0.1.9'
  pod 'LNLiveModule', '~>0.1.5'
  pod 'LNVideoModule', '~>0.1.5'
  pod 'LNUserCenterModule', '~>0.1.5'
    # Local pod
#  pod 'LNModuleCore', :path => '../LNModuleCore'
#  pod 'LNModuleProtocol', :path => '../LNModuleProtocol'
#  pod 'LNCommonKit', :path => '../LNCommonKit'
#  pod 'LNAccountModule', :path => '../LNAccountModule'
#  pod 'LNFeedModule', :path => '../LNFeedModule'
#  pod 'LNVideoModule', :path => '../LNVideoModule'
#  pod 'LNLiveModule', :path => '../LNLiveModule'
#  pod 'LNUserCenterModule', :path => '../LNUserCenterModule'
#  pod 'LNDownloader', :path => '../LNDownloader'
  target 'ArchitectureDesignTests' do
    inherit! :search_paths

    # pod 'FBSnapshotTestCase'
  end
end


#post_install do |installer|
#    ## Fix for XCode 12.5
#    find_and_replace("Pods/FBRetainCycleDetector/FBRetainCycleDetector/Layout/Classes/FBClassStrongLayout.mm",
#      "layoutCache[currentClass] = ivars;", "layoutCache[(id<NSCopying>)currentClass] = ivars;")
#end
