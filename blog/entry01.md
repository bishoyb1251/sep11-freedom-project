# Entry 1
##### 10/28/24

##### What tool have I decided on?
Me and my partner Omar have decided on making a shooting/sports game using impactjs. Impactjs is a Javascript Game Engine that allows you to develop HTML5 games.

##### Why do I want want to do this?
I want to make a game with impactjs because me and my partner Omar are intrested in sports like soccer. We also chose impact because out of the many game engines there are impact really caught our eyes. They introduced us to their website with a shooting game that was given to the user to be able to play.

##### Some code I tinkered with?
```js
ig.module(
    'game.main'
)
.requires(
    'impact.game',
    'impact.debug.debug',
    'game.levels.basic'
)

.defines(function(){
    MyGame = ig.Game.extend({
        init: function(){
            this.loadLevel(LevelBasic);
        }

    });
    // Create an instance of our game
    ig.main('#canvas', MyGame, 60, 320, 240, 2);
});
```

#### What is this code?
When I was tinkering I found out this is the code I put in the impactjs creation module.

#### What are some more codes I found on the impactsjs github?
```js
ig.module(
	'impact.animation'
)
.requires(
	'impact.timer',
	'impact.image'
)
.defines(function(){ "use strict";

ig.AnimationSheet = ig.Class.extend({
	width: 8,
	height: 8,
	image: null,

	init: function( path, width, height ) {
		this.width = width;
		this.height = height;

		this.image = new ig.Image( path );
	}
});
```
* This would be the first line of code that I would create the game with.



[Next](entry02.md)
[Home](../README.md)
