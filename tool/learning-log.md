# Tool Learning Log

## Tool: **KABOOOM.JS**

## Project: **Impact.js**

---

### 10/15/24:
* I used kaboom.js.com to be able to see the code that kaboom and or game pages uses to be able to make games.
https://github.com/replit/kaboom Is what I saw to see some code that I needed for kaboom.js

I also used https://impactjs.com/ to be able to play a game that was on the website which is a shooting game.

### 10/16/24:
* Some things that I tried was using some of the code that I saw on kaboom.js to try to imitate what I saw on the impact.js


### 11/17/24
* Some things I tried using to learn impact was trying some code out on jsbin. This code bascicaly helps make the layout of the game.I used github and impactjs for a reference.
```jsig.module(
	'game.main'
)
.requires(
	'impact.game',
	'impact.font'
)
.defines(function(){

MyGame = ig.Game.extend({

	// Load a font
	font: new ig.Font( 'media/04b03.font.png' ),


	init: function() {
		// Initialize your game here; bind keys etc.
	},

	update: function() {
		// Update all entities and backgroundMaps
		this.parent();

		// Add your own, additional update code here
	},

	draw: function() {
		// Draw all entities and backgroundMaps
		this.parent();


		// Add your own drawing code here
		var x = ig.system.width/2,
			y = ig.system.height/2;

		this.font.draw( 'It Works!', x, y, ig.Font.ALIGN.CENTER );
	}
});


// Start the Game with 60fps, a resolution of 320x240, scaled
// up by a factor of 2
ig.main( '#canvas', MyGame, 60, 320, 240, 2 );

});
```
<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
