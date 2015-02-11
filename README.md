# Phaser Tiled map Spritesheet Sample

### Disclaimer
See [LICENSE.md]() for license terms and conditions.

This sample is used to show the usage of Tiled map in Phaser engine with 
Intel(R) XDK. The assets and code are created from [phaser-sidescroller](https://github.com/fariazz/phaser-sidescroller) by Kenney.

### Application Files
* asset/
  *screenshots/
  *spritesheets/
* css/
  *app.js
* index.html
* js/
  *Boot.js
  *Game.js
  *gamecontroller.js
  *gamecontroller.min.js
  *main.js
  *phaser.js
  *phaser.min.js
  *Preload.js
* xdk/
  *init-dev.js


### Overview

`www/js/app.js` is the entrance of the game which defines and bootstrap following scenarios (or states):
* [Preload](www/js/Preload.js): load assets for the game
* [Boot](www/js/Boot.js): setting game configuration and loading the assets for the loading screen
* [Gamecontroller](www/js/gamecontroller.js): controlling roles in game
* [Game](www/js/Game.js): main game logic
* [Main](www/js/main.js): setup game

