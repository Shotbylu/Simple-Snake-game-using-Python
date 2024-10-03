Snake Game
This is a simple Snake Game implemented using Pygame. The objective of the game is to control the snake to eat food, grow longer, and avoid collisions with the walls or itself.

Features
Classic snake gameplay
Increasing difficulty with levels
Score tracking
Start and Game Over screens
Requirements
Python 3.x
Pygame library
Installation
Clone the repository:
git clone https://github.com/yourusername/snake-game.git
cd snake-game

Install Pygame:
pip install pygame

How to Play
Run the game:
python snake_game.py

Controls:
Arrow keys to change the direction of the snake.
Press SPACE to start or restart the game.
Code Overview
snake_game.py: The main game file containing all the game logic.
Classes:
Snake: Manages the snake’s position, movement, and collision detection.
Game: Manages the game state, including the screen, events, and game loop.
Functions:
reset_game(): Resets the game state.
generate_food(): Generates food at random positions.
draw(): Draws the game elements on the screen.
handle_events(): Handles user input.
update(): Updates the game state.
show_start_screen(): Displays the start screen.
show_game_over(): Displays the game over screen.
run(): Runs the main game loop.
Screenshots
!Start Screen !Game Screen !Game Over Screen

License
This project is licensed under the MIT License. See the LICENSE file for details.
