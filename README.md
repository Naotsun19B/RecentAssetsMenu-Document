# RecentAssetsMenu

![Plugin](https://user-images.githubusercontent.com/51815450/220249566-4c5cbf51-1584-4a9e-8fde-17d7f79f089c.PNG)

<!--ts-->
   * [Description](#Description)
   * [Requirement](#Requirement)
   * [Installation](#Installation)
   * [Usage](#Usage)
   * [License](#License)
   * [Author](#Author)
   * [History](#History)
<!--te-->

## Description

This plugin adds a menu to the file menu to open recently opened assets as well as level assets.  
In UE5.3 and later, the functionality added by this plugin is included in the engine as standard.  
~~I plan to make it compatible with the latest version so that similar functions can be used in UE5.2 and earlier versions from the Marketplace, but from UE5.3 onwards, this plugin will essentially be an empty plugin that does nothing.~~  
Fab now supports any engine version, so I have removed support for UE5.3 and later.

## Requirement

Target version : UE4.27 ～ 5.2  
Target platform : Windows, Mac, Linux 

## Installation

Put the [Plugins/RecentAssetsMenu](https://github.com/Naotsun19B/RecentAssetsMenu) folder in your project's Plugins folder.  
Or install from the [marketplace](https://www.unrealengine.com/marketplace/en-US/product/recent-assets-menu).  
If the feature is not available after installing the plugin, it is possible that the plugin has not been enabled, so please check if the plugin is enabled from Edit > Plugins.

## Usage

A menu called "Recent Assets" has been added to the file menu, so select the asset you want to open from there.  

![Usage](https://user-images.githubusercontent.com/51815450/224694011-d5fe8c8e-9ca2-40eb-a78e-9d318ce1a715.PNG)

You can also change the shortcut keys from the keyboard shortcuts in the editor preferences.

![KeyboardShortcuts](https://user-images.githubusercontent.com/51815450/224676158-39f559ca-495e-4e89-985d-7a21af53ba5f.PNG)

## License

[MIT License](https://en.wikipedia.org/wiki/MIT_License)

## Author

[Naotsun](https://twitter.com/Naotsun_UE)

## History  

- (2025/06/08) Development finished    
  Support for UE5.3 and later has been discontinued  

- (2024/04/24) v1.4   
  Added support for UE5.4

- (2023/09/07) v1.3   
  Added support for UE5.3  

- (2023/05/14) v1.2   
  Added support for UE5.2

- (2023/03/13) v1.1   
  Added a menu to clear data for recently opened assets

- (2023/02/15) v1.0   
  Publish plugin
