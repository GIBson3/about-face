![GitHub release](https://img.shields.io/github/release-date/mclemente/about-face)
![all versions](https://img.shields.io/github/downloads/mclemente/about-face/total) 
![the latest version](https://img.shields.io/github/downloads/mclemente/about-face/latest/total) 
![Forge installs](https://img.shields.io/badge/dynamic/json?label=Forge%20Installs&query=package.installs&suffix=%25&url=https%3A%2F%2Fforge-vtt.com%2Fapi%2Fbazaar%2Fpackage%2Fabout-face)

# About Face -- FoundryVTT Module
About Face is a module for FoundryVTT that changes a token's direction based on movement. It also provides optional "facing" indicators for tokens.

![Example](https://github.com/League-of-Foundry-Developers/about-face/raw/master/AboutFace-Demo.gif)

## Installation
Simply use the install module screen within the FoundryVTT setup

## Usage
Two options are available in the game settings module config. Otherwise, with everything enabled:
- Move your token!
- Hold SHIFT and using your W,A,S,D or &#8593;,&#8592;,&#8595;,&#8594; you can change the direction your token is facing without moving

### Disable for a specific Token
![Token Config Screenshot](https://raw.githubusercontent.com/League-of-Foundry-Developers/about-face/master/screenshot.PNG)

## Known Issues / Limitations
- If a token is not facing down just edit the rotation in Token Config > Image.

## Troubleshooting
#### How do I keep certain tokens from spinning?
- You can lock tokens by either double-clicking and selecting the token icon from the hud or accessing from the character sheet. The option you're looking for is "Lock Rotation" under the "Position" tab.

## Credit
Eadorin & edzillion, for the original [About Face](https://github.com/League-of-Foundry-Developers/about-face).
Assistance from several Discord users, including @Forien and @Stan. Accepting translations for the few config options.

## License
This Foundry VTT module is a fork of [About Face](https://github.com/League-of-Foundry-Developers/about-face) and is licensed under [GNU GPLv3.0](https://www.gnu.org/licenses/gpl-3.0.en.html), supplemented by [Commons Clause](https://commonsclause.com/).

This work is licensed under Foundry Virtual Tabletop [EULA - Limited License Agreement for module development v 0.1.6](http://foundryvtt.com/pages/license.html).
