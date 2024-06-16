# Stack Block Game

Stack Block Game is a JavaScript-based project that challenges players to stack blocks on top of each other, aiming to build the tallest tower possible. The objective is to precisely position each block; the game concludes if a block is inaccurately placed on the stack.

## Overview

This game utilizes HTML, CSS, and JavaScript alongside Three.js and Cannon.js libraries to create an interactive and visually engaging stacking experience. By leveraging physics simulations, it offers players an immersive and challenging gameplay environment.

## Features

### Autopilot Mode

The game offers an autopilot mode, allowing it to play itself automatically. This feature showcases various stacking strategies and techniques.

### Input Cooldown

To prevent rapid and unintentional inputs, a 500 milliseconds cooldown period is enforced between consecutive inputs. This enhances gameplay by promoting thoughtful and deliberate actions.

### Game Reset

Players can reset the game at any point by pressing the 'R' or 'r' key. This functionality provides convenience and allows for restarting the game seamlessly.

## Core Functions

### `eventHandler()`

This function manages game input events. In autopilot mode, it initiates the game. Otherwise, it calls the `splitBlockAndAddNextOneIfOverlaps()` function.

### `splitBlockAndAddNextOneIfOverlaps()`

Responsible for handling the logic of splitting blocks and adding the next one. It computes sizes, deltas, overhangs, and overlaps. When an overlap occurs, a click sound is triggered, and the block is cut accordingly.

### `resetGame(event)`

Initiates a game reset when triggered by the 'R' or 'r' keypress. It prevents the default action and starts the game afresh, providing users with a convenient restart option.

## How to Play

1. **Game Start**: Launch the game by pressing the 'R' or 'r' key.
2. **Stacking Strategy**: Precisely stack the blocks to create a towering structure.
3. **Game End**: If a block is inaccurately placed, the game concludes.
4. **Reset**: To restart the game, press the 'R' or 'r' key again.

## Getting Started

To run the game locally:

1. Clone this repository: `git clone https://github.com/your-username/stack-block-game.git`
2. run "npm i" to install any dependencies
3. Navigate to the project directory: `cd stack-block-game`
4. Open `index.html` in a web browser.

Alternatively, the game is accessible online  [Here](https://stack-game-pearl.vercel.app/).

## Credits

- **Open Source Libraries**:
  - [Three.js](https://threejs.org/)
  - [Cannon.js](https://github.com/schteppe/cannon.js/)

