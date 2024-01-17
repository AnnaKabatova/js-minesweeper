# Minesweeper Game

## Overview
This is a classic Minesweeper game implemented in JavaScript, HTML, and CSS. It follows the rules of the traditional Minesweeper game, allowing you to uncover tiles and avoid mines. You can restart the game or customize the number of mines.

## Features
- Classic Minesweeper gameplay.
- Restart button to reset the game.
- Option to set the number of mines.

## Project Setup
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd minesweeper-game
2. Open index.html in your web browser and play.

## Board Size
Default board size is set to 400x400 pixels, each tile is 50x50 px. If you'd like to change that:
1. Locate `#board` part in minesweeper.css and change `width` and `height` parameters to other numbers (they both should be multiples of 50)
2. In the beginning of minesweeper.js change the number of `rows` and `colums` that will be equal your width/50 and height/50 respectively.

## How to Play
### Uncover Tiles
Left-click on a tile to uncover it.

### Flag Mines
Click on the flag button and then on the tile where you'd like to put a flag. After you're done, click on flag button again and continue.

### Gameplay
- Avoid clicking on tiles containing mines.
- Use the restart button to begin a new game.
- Use Mines input to set you custom number of mines.

## Screenshots
1. New game
![started over](https://github.com/AnnaKabatova/js-minesweeper/assets/80786573/65599f30-b5e6-4fe5-bdb8-84eaeabe48ed)

2. Game ended successfully
![mines_cleared](https://github.com/AnnaKabatova/js-minesweeper/assets/80786573/11feb440-de48-49b9-b8c6-b0b1228de487)

3. You've clicked on a mine, game over!
![game over](https://github.com/AnnaKabatova/js-minesweeper/assets/80786573/bce5ea29-6535-46c3-9df2-c00dc849e52b)
