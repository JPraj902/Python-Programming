# Tic-Tac-Toe Game

This is a simple Tic-Tac-Toe game built using Python's Tkinter library for the GUI, and NumPy for internal logic.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Game Flow](#game-flow)
- [Technologies Used](#technologies-used)

## Features
- Play Tic-Tac-Toe against another player on the same device.
- Score tracking for Player 1 (X), Player 2 (O), and ties.
- Game board automatically resets for a new game after a win or a tie.
- Graphical user interface (GUI) created using Tkinter.
- Color-coded symbols:
  - X in Red (`#EE4035`)
  - O in Blue (`#0492CF`)

## Installation
1. Clone this repository:
    ```
    git clone https://github.com/your-username/tic-tac-toe
    ```
2. Install the required dependencies:
    ```
    pip install numpy
    ```
3. Run the game:
    ```
    python main.py
    ```

## How to Play
- The game starts with Player X's turn. Player O follows.
- Click on a grid cell to place your mark (X or O).
- The first player to align three marks in a row, column, or diagonal wins.
- In case of a tie, the game will display a tie message.

## Game Flow
1. The game window initializes with an empty 3x3 grid.
2. Players take turns clicking on the grid to place their marks.
3. The game checks for a winner or a tie after each move.
4. After the game is over, the result is displayed, and the board resets for a new game when clicked.

## Technologies Used
- **Python** for game logic and main functionality.
- **Tkinter** for creating the graphical user interface (GUI).
- **NumPy** for handling the internal game board and status checks.
