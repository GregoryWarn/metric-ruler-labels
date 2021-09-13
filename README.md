![](https://img.shields.io/badge/Foundry-v0.8.9-informational)
<!--- Downloads @ Latest Badge -->
<!--- replace <user>/<repo> with your username/repository -->
<!--- ![Latest Release Download Count](https://img.shields.io/github/downloads/Roger92/metric-ruler-labels/latest/module.zip) -->

<!--- Forge Bazaar Install % Badge -->
<!--- replace <your-module-name> with the `name` in your manifest -->
<!--- ![Forge Installs](https://img.shields.io/badge/dynamic/json?label=Forge%20Installs&query=package.installs&suffix=%25&url=https%3A%2F%2Fforge-vtt.com%2Fapi%2Fbazaar%2Fpackage%2Fmetric-ruler-labels&colorB=4aa94a) -->

# Roger's Additional Metric Ruler Labels

For everyone that uses the metric system in the real world and wants to know the metric distances without changing the DnD system.

GM:
> There is a 20 feet wide gorge upon your party. What do you do?

*You are asking yourself:* 
> 20 feet ... is this wide? Should i try jumping across it?

<br>
This module will help you to better understand distances. <br>
It adds additional labels for the metric measurements to your ruler. It is not changing any systems etc. It only applies an additional label to the UI.

### The following units are supported:

- ft, ft. and feet will get converted to meters (5 ft -> 1,5 m)
- mi, mi., and miles will be converted to kilometers (1 mile -> 1,61 km)

## Example feet to meters
![ezgif com-gif-maker](https://user-images.githubusercontent.com/11605051/133088579-ca09a91c-ea11-4d2a-b53a-1e5adfac374a.gif)

## Example miles to kilometers
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/11605051/133089023-0cf26ee0-e310-491e-ba12-80990d1e3598.gif)

## Compatibility
I only tested it with FoundryVTT 0.8.9 but it should work with other versions that the two dependencies support (0.8.5 and later)

## Dependencies
- libWrapper from ruipin https://foundryvtt.com/packages/lib-wrapper/
- libRuler from ceawok https://foundryvtt.com/packages/libruler

## Planned
Add this feature also to the measurement templates like cone, circle, rectangle and ray

## Changelog
- v0.9.0 First realease with the conversions for miles and feet for the ruler tool.
