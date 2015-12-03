AvatarDuty: Hackday Project with Phaser.io
==========================================

I hacked some marketing video assets into a fun avatar maker for a PagerDuty hackday personal project. [Make your avatar](http://daverau.info/avatarduty/) in fun 8-bit retro-style artwork.

<img src="https://raw.githubusercontent.com/redlabor/avatarduty/master/demo-images/grid.png">


Background
----------
I wanted to explore the Phaser.io game framework, so this was an experiment that was both a technical/learning challenge as well as a fun visual exploration in creating some modular people parts.

Starting in Adobe Illustrator I created variations on face shapes then moved onto changing background colors, finally adding some fun 8-bit theme sound effects and a save-to-png option.

Interface in action
-------------------
<img src="https://raw.githubusercontent.com/redlabor/avatarduty/master/demo-images/ui-demo.gif" width="320" >

Features
--------

* choose between guy or girl faces
* choose your face, eyes, mouth, shirt, hair and beard
* 8-bit retro sound effects
* change background colors
* randomize all button
* save to png

Recently...
---------

* pushed to this repo
* updated code to not look broken on retina screens
* updated SVG assets with new sizes and colors
* reverted retina fix (Despite using SVG, which is not natively supported in Phaser, the assets don't scale as cleanly as I'd like on Retina/high-dpi screens, so best viewed a normal 72dpi screen.)
* tried using Phaser component output (grunt custom --exclude gamepad,p2,tilesprite,retrofont,video,rope,net,tweens,flexgrid,color,debug,ninja,creature,tilemaps,particles --filename phaser-drau --uglify true) but not 100% working yet...