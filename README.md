# 2048 Game in Python with Tkinter

## Overview

This simple 2048 game is implemented in Python using the Tkinter library for the graphical user interface. The game starts with a 4x4 grid, and the player needs to combine matching numbered tiles to reach the coveted 2048 tile.

## Features

- **Colorful UI:** The game features a colorful user interface with different background and text colors for each tile value.

- **Responsive Controls:** Use the arrow keys (Up, Down, Left, Right) to move the tiles on the grid.

- **Scoring System:** The game keeps track of your score as you merge tiles. The goal is to reach the 2048 tile.


## Gameplay

### Starting the Game:

1. The game begins with two random tiles of value 2 placed on the grid.
2. Use the arrow keys to move the tiles in the corresponding direction.

### Merging Tiles:

- When two tiles with the same value collide, they merge into a new tile with double the value.
- The merged tile contributes to your score.

### Winning and Losing:

- The game ends when you reach the 2048 tile, resulting in a victory.
- If the grid is full, and no more moves can be made, the game ends, and you lose.

### Scoring:

- Your score is displayed on the console.
- Successfully merging tiles increases your score.

## Getting Started

To run the game, simply execute the provided Python script:

```bash
python 2048_game.py
```
