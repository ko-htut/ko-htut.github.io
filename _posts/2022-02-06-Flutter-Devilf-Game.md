---
layout:     post
title:      Flutter Devilf Game
subtitle:   devilf game 
date:       2022-02-06
author:     Ko Htut
header-img: img/flutter.jpg
catalog: true
tags:
    - Flutter
    - Games
    - Devilf
---

# DevilF 游戏引擎  
<p align="center" >
    <img src="https://github.com/ym6745476/devilf/blob/master/logo.png?raw=true" />
</p>

<p align="center">
    <img src="https://img.shields.io/badge/devilf-0.1.0-orange" />
    <img src="https://img.shields.io/badge/flutter-2.5.0-green" />
</p>

<p align="center" >
    A Flutter 2D RPG Game Engine On Web & Android & IOS.
</p>
<p align="center" >
    A Flutter-based 2D RPG game engine.
</p>
  
<p align="center" >
   The Devilf Engine Is A Open Source 2D Game Engine.
   The Engine Is Development Using Flutter & Dart Language.
   You Can Use It Independently In Your Flutter Project.
   Some Documentation Of How To Use It Can Be Found Here.
</p>

## Engine introduction
Flutter is built by a team of engineers at Google to create high-performance, cross-platform mobile applications.
Using Flutter can easily achieve three-terminal cross-platform, providing more possibilities for APP gamification and cross-platform game development.
Thank you for your attention, and welcome to contribute your ideas and technologies. Welcome to join the QQ group discussion: 687500695! ! !
Statement: The material in the game comes from Legendary World. If there is any infringement, please contact the webmaster to delete it. The material is only for development and learning. The consequences of abuse have nothing to do with this site.
## Scope of application:
Medium games, marketing campaigns, small games.

## Main features:
Game looping, sprite rendering, sprite animation, cameras, tile maps, collision detection, and more.

## Engine official website
https://devilf.com

## Development Manual
https://ymbok.com/book/devilf.html

## online experience    
https://ymbok.com/download/slayer.html

## Screenshot

<img src="https://github.com/ym6745476/devilf/blob/master/screenshot/slayer.gif?v=10" width="600" height="292"/> 

## Example function
* GameManager: Game Manager
* GameScene: Game scene
* PlayerSprite: player sprite
* MonsterSprite: Monster Sprite
* EffectSprite: special effect sprite
* MapSprite: map sprite
* ItemSprite: item sprite

## core components
* GameScene: Game scene
* GameWidget: Game controls
* GameRenderBox: render controls
* GameLoop: game loop
* Sprite: sprite class
* Camera: camera
* Audio: sound effects

## sprite rendering
* TextSprite: Text sprite
* ImageSprite: Image sprite
* AnimationSprite: animation sprite
* ProgressSprite: progress sprite
* TileMapSprite: tile sprite

## Game controls
* Joystick: Joystick
* Button: button
* CheckButton: select button

## Game features
* Resource loading
* Impact checking  
* Coordinate conversion
* A* pathfinding algorithm

## [0.1.0] - 2021/09/26.
* Upgrade [core] Flutter 2.5.0
* Added [Example] item pickup function
* Added [Example] items dropped into the scene to display
* Added [Example] monster death item drop configuration
* Added [Example] Equipment information display
* Added [Core] sprite to listen for click events

## [0.0.9] - 2021/08/19.
* Optimize [Example] Fix BUG
* Added [Example] Backpack page of character interface
* Added [Example] data configuration file
* Optimized [Example] map movement range limit
* Added [Example] monster snake, dummy, two weapon materials
* Added [Example] player and monster motion and battle sound effects

##[0.0.8] - 2021/08/15.
* Optimize [Example] Fix BUG
* Optimization [Core] Code logic optimization
* Added [core] sound effects class

## [0.0.7] - 2021/08/10.
* Optimization [Example] Automatic battle logic optimization
* Optimized [Example] Protagonist and monster A* seek target
* Added [Core] A* Best Path Algorithm
* Added [core] collision shape collision function
* Added [Core] Draw occlusion layer and collision layer

## [0.0.6] - 2021/08/01.
* Optimized [Example] skill area button layout
* Added [Core] button control
* Added [Core] Dynamic loading of map tiles
* Added [Core] Camera main character follow
* Added [Example] Tiled map display
* Added [Core] Added tile sprites
* Optimized [core] joystick not fixed position
* Added [Example] Added health bar display for players and monsters
* Added [Core] Progress Sprite
* Added [Example] Target Lock Auto Move Auto Battle
* Added [Example] Attack and Kill Swordsmanship and Small Fireball Effects
* Added [Example] monster death animation
* Added [Example] Added spider monster

## [0.0.5] - 2021/07/16.
* Optimized [core] engine code and examples

## [0.0.4] - 2021/07/15.
* Added [Example] joystick to control player movement
* Added [core] Joystick control

## [0.0.3] - 2021/07/11.
* Added [Example] Sprite rendering
* Optimize [core] Rename all classes to add DF prefix
* Added [Core] Read the Plist to Json file format exported by TexturePacker
* Added [core] AnimationSprite animation sprite
* Added [core] ImageSprite image sprite
* Added [core] TextSprite text sprite

## [0.0.2] - 2021/07/07.
* Added [core] GameScene game scene
* Added [Core] AssetsLoader resource reading
* Added [core] GameRenderBox rendering box

## [0.0.1] - 2021/07/06.
* Added [core] GameLoop game loop
* Added [core] GameWidget game controls
* Added [core] Sprite base sprite class