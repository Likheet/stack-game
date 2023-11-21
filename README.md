# Stack Block Game
This JavaScript project is a game where blocks are stacked on top of each other. The player's goal is to stack as many blocks as possible. The game ends when a block is not placed correctly on the stack.
## Tech Stack: HTML, CSS, JavaScript, Three.JS, Cannon.JS, WebGUI

# Key Features
## Autopilot Mode: 
The game can be set to autopilot mode, where it automatically plays itself.
## Input Cooldown: 
To prevent rapid, unintentional inputs, an input cooldown of 500 milliseconds is implemented.
## Game Reset: 
The game can be reset and started again by pressing the 'R' or 'r' key.
Core Functions
## eventHandler(): 
This function handles the game's input events. If the game is in autopilot mode, it starts the game. Otherwise, it calls the splitBlockAndAddNextOneIfOverlaps() function.
## splitBlockAndAddNextOneIfOverlaps(): 
This function handles the logic for splitting the blocks and adding the next one. It calculates the size, delta, overhang size, and overlap of the top layer and the previous layer. If there is an overlap, it plays a click sound and cuts the box.
## resetGame(event): 
This function resets the game. It prevents the default action and starts the game.

# How to Play
Start the game by pressing the 'R' or 'r' key.
Stack the blocks as accurately as possible. The game ends when a block is not placed correctly on the stack.
To reset the game, press the 'R' or 'r' key again.