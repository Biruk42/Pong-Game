# Pong Game

## Overview
This is a Pong Game implemented using the Turtle module in Python. Players control paddles to hit a ball back and forth, with the goal of scoring points by causing the opponent to miss the ball.

## Requirements
- Python 3.x
- Turtle module

## Usage
1. Run the script.
2. Player 1 controls the right paddle using the Up and Down arrow keys.
3. Player 2 controls the left paddle using the "w" and "s" keys.
4. The ball will move automatically, bouncing off walls and paddles.
5. Each time the ball misses a paddle and goes out of bounds, the opponent scores a point.
6. The game continues until one player reaches the winning score.

## Components
- `Paddle`: Represents the paddles controlled by each player.
- `Ball`: Represents the ball object and its movements.
- `Scoreboard`: Displays the current score for each player.

## Features
- Smooth animation using Turtle's screen.update() and time.sleep().
- Collision detection with walls, paddles, and the ball's movement.
- Score tracking and display using the Scoreboard.

## Note
- Ensure that you have the necessary dependencies installed.
- Adjust the screen dimensions, paddle speed, and ball speed in the code to modify the game's difficulty and appearance.

## Contributions
Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request.
