Frustration Game
This is a simple, two-player endless runner-style game built using HTML5 Canvas and vanilla JavaScript. Two players, represented by stick figures, compete to "visit" as many doors as possible while navigating a field of obstacles.

Features
Two-Player Gameplay: Use a single keyboard to control two separate stickmen.

Dynamic Obstacles: Avoid static mines and "goo traps" that freeze you in place.

Inverted Controls: The game challenges players by randomly inverting their movement controls.

Sound Effects: Enjoy retro-style sound effects for events like scoring, explosions, and getting stuck.

Endless Mode: The game is an endless high-score challenge.

Boss Fight Mode: Reach a certain score to trigger a boss fight where the two stickmen merge into a single, larger character.

How to Play
Controls
Player 1 (White Stickman)

Move: W, A, S, D keys

Toggle Gun: G

Shoot: F

Activate Shield: C (Hold down to keep the shield active)

Player 2 (Cyan Stickman)

Move: Arrow keys

Toggle Gun: P

Shoot: Enter

Activate Shield: L (Hold down to keep the shield active)

Game Rules
Navigate your stickman to the blue doors that appear on the screen to score points.

Be careful! Controls may randomly invert when a player scores. The status text at the top of the screen will let you know if your controls are "NORMAL" or "INVERTED."

Avoid the static mines (cyan circles) and goo traps (green circles). Hitting a mine ends the game. Stepping in goo freezes you temporarily.

The first player to reach a score of 5 (combined total) will trigger a "Boss Fight" mode.

In Boss Fight mode, the two stickmen merge into a single, larger stickman with its own set of controls and a new objective.

You can shoot at the other player with your gun to win the game, but be careful not to get shot yourself!

The game ends when a player hits a mine, a player gets shot, or the merged stickman hits a mine in the boss fight.

The "Play Again" button restarts the game from the beginning.

The "Restart from Checkpoint" button, which appears after a game over in the boss fight, lets you restart the boss fight with your score intact.

Technical Details
HTML: Sets up the basic page structure, canvas, and game interface elements like the scoreboards and game over screen.

CSS: Styles the game, providing a full-screen, minimalist black and white aesthetic with a clean interface. It also includes animations for the game over screen.

JavaScript: The core game logic.

Uses HTML5 Canvas for all game drawing.

Handles player movement, collisions, and scoring.

Implements game states such as isGameOver, isMerged, and isTransitioning.

Manages power-ups like the gun and shield.

Uses the Tone.js library for all in-game sound effects. This provides a simple way to generate chiptune-style sounds.

Customization
You can easily modify the game by editing the script tag in the index.html file. Here are a few variables you might want to change:

numMines: Adjusts the number of mines on the screen.

numGooTraps: Adjusts the number of goo traps.

stickman1.color and stickman2.color: Change the color of each stickman.

door.color: Change the color of the door.

stickman.speed: Increase or decrease the player's movement speed.

The scores required to trigger the boss fight.
