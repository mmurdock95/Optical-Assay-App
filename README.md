# assay-analysis

Assay analysis project for Capstone (CPE 350).

Authors: Anthony Annuzzi, Justin Zaman, David Zhuo
Winter Quater, 2016

Build Target: iOS 10


# Installation

1. Be sure Xcode is closed
2. Run the following commands to install cocoapods

		sudo gem install cocoapods
		pod setup
		pod install

2a. If you're updating packages and not installing them new

                pod update
		
3. Open the workspace (.xcworkspace not .xcodeproj)
4. Build and deploy


# Important Directories/Files

cv-prototyping: OpenCV prototyping code, in both python and C++. This also contains some NEW sample photos to use for prototyping.
_For fast prototyping, replace the cv-prototyping .cpp files with symlinks to the Xcode project's versions. Git does not respect symlinks. This also implies that there are two versions of the computer vision c++ code because of git!!!_

Podfile: Defines which external packages to use and which version
Frameworks: Contains the OpenCV library
old-wellphotos: This was the last group's set of pictures