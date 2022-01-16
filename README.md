[![Version (latest)](https://img.shields.io/github/v/release/Roger92/metric-ruler-labels)](https://github.com/Roger92/metric-ruler-labels/releases/latest)
[![Foundry Version](https://img.shields.io/badge/dynamic/json.svg?url=https://github.com/Roger92/metric-ruler-labels/releases/latest/download/module.json&label=Foundry%20Version&query=$.compatibleCoreVersion&colorB=blueviolet)](https://github.com/Roger92/metric-ruler-labels/releases/latest)
[![GitHub downloads (latest)](https://img.shields.io/badge/dynamic/json?label=Downloads@latest&query=assets[?(@.name.includes('zip'))].download_count&url=https://api.github.com/repos/Roger92/metric-ruler-labels/releases/latest&color=green)](https://github.com/Roger92/metric-ruler-labels/releases/latest)
[![Forge Install Base](https://img.shields.io/badge/dynamic/json?label=Forge%20Install%20Base&query=package.installs&suffix=%&url=https://forge-vtt.com/api/bazaar/package/metric-ruler-labels&colorB=brightgreen)](https://forge-vtt.com/)
[![Ko-fi](https://img.shields.io/badge/-buy%20me%20a%20coffee-%23FF5E5B?logo=Ko-fi&logoColor=white)](https://ko-fi.com/roger92)
# Roger's Additional Metric Ruler Labels

For everyone that uses the metric system in the real world and wants to know the metric distances without changing the underlying game system.

GM:
> A 20 feet wide gorge lies ahead of your party. What do you do?

*You are asking yourself:* 
> 20 feet ... is this wide? Should i try jumping across it?

<br>
This module will help you to better understand distances. <br>
It adds additional labels for the metric measurements to your ruler. It is not changing any systems etc. It only applies an additional label to the UI.

## V9 - Compatability
Its compatible with V9 - Checked ob Build 242. Please note that Release 1.1.0 and above are not compatible with foundry versions below V9 :)

## Table of Contents

  * [The following units are supported:](#the-following-units-are-supported)
  * [Example feet to meters](#example-feet-to-meters)
  * [Example miles to kilometers](#example-miles-to-kilometers)
  * [Works with FoundryVTT's MeasureTemplates](#works-with-foundryvtts-measuretemplates)
  * [Support for other packages](#support-for-other-packages)
    +  [DragRuler](#dragruler)
  * [Installation](#installation)
  * [Compatibility](#compatibility)
  * [Dependencies](#dependencies)
  * [Planned](#planned)
  * [Feedback](#feedback)
  * [Changelog](#changelog)

## The following units are supported

- ft, ft. and feet will get converted to meters (5 ft -> 1,5 m)
- mi, mi., and miles will be converted to kilometers (1 mile -> 1,61 km)

## Example feet to meters
![Ruler](https://user-images.githubusercontent.com/11605051/133685368-75476211-907a-43fb-8aa9-400e7aa9171c.gif)

## Example miles to kilometers 
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/11605051/133089023-0cf26ee0-e310-491e-ba12-80990d1e3598.gif)

## Works with FoundryVTT's MeasureTemplates
![measureTemplates](https://user-images.githubusercontent.com/11605051/133858694-eea1b96e-3524-4725-b889-37dec98e2a74.gif)

## Support for other packages
### DragRuler
This module now supports the [DragRuler](https://foundryvtt.com/packages/drag-ruler) module from Stäbchenfisch. You can enable/disable the labels in the settings.
![DragRuler](https://user-images.githubusercontent.com/11605051/133684447-e5f09288-7495-4987-a26e-f5300c811a72.gif)


## Installation
To install, follow these instructions:

1. Inside Foundry, select the "Add-on Modules" tab in the Configuration and Setup menu.
2. Click the Install Module button and enter the following URL: https://github.com/roger92/metric-ruler-labels/releases/latest/download/module.json or search for Metric Ruler Labels in the search.
3. Click Install and wait for installation to complete.

## Compatibility
I only tested it with FoundryVTT 0.8.9 but it should work with other versions that the two dependencies support (0.8.5 and later).

## Dependencies
- libWrapper from ruipin https://foundryvtt.com/packages/lib-wrapper/

Also thanks to ruipin for the libWrapper module :)

## Planned
Nothing right now. :)

## Feedback
If you find a bug or have any feedback for me just add an issue in the [issuetracker](https://github.com/Roger92/metric-ruler-labels/issues). Thx alot and i hope this module helps you in your game :)

## Changelog
**v1.1.0**
- Added support for V9
- Fixed MeasureTemplates support that didn't work anymore in V9

**v1.0.0**
- Added support for FoundryVTT's MeasureTemplates

**v0.9.1**
- Added support for the DragRuler module by Stäbchenfisch ( you can activate/deactivate metric labels for this module in the settings)
- All segments of the ruler now have metric labels
- Added german localization
- Added a dialog if dependency is missing
- Removed libRuler as a dependency  (yay ... less dependencies are always better \\(°0°)/ )

**v0.9.0**
- First realease with the conversions for miles and feet for the ruler tool.
