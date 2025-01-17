# Snake Game

## Overview
This is a classic Snake game implemented in Python using the Pygame library. The game features a growing snake that moves around the screen, eating food to increase its length while avoiding collisions with itself and the screen boundaries.

## Features
- Smooth snake movement
- Collision detection
- Increasing difficulty with levels
- Start and Game Over screens
- Score and level display

## Requirements
Ensure you have Python installed along with the Pygame library. You can install Pygame using the following command:
```sh
pip install pygame
```

## How to Play
1. Run the script using:
   ```sh
   python snake_game.py
   ```
2. Press `SPACE` to start the game.
3. Control the snake using the arrow keys:
   - `UP` to move up
   - `DOWN` to move down
   - `LEFT` to move left
   - `RIGHT` to move right
4. Eat the red food to grow longer and increase your score.
5. Every 5 points, the level increases, and the game speed increases.
6. Avoid colliding with the screen boundaries and yourself.
7. If you lose, press `SPACE` to restart the game.

## Game Elements
- **Snake**: The player-controlled entity that moves in a chosen direction.
- **Food**: Appears randomly on the screen; eating it increases the snake's length and score.
- **Score**: Displayed on the top-left corner, increases when the snake eats food.
- **Level**: Shown on the top-right, increases every 5 points.
- **Game Over Screen**: Shown when the snake collides with itself or the wall.

## Code Structure
- `Snake` class: Manages snake movement, growth, and collision detection.
- `Game` class: Handles the game loop, events, rendering, and score management.
- `Main loop`: Runs the game, checking for user input and updating the screen accordingly.

## Future Improvements
- Add sound effects
- Implement a high-score system
- Introduce obstacles for additional difficulty
- Enhance graphics with better animations

## Author
Developed by Lungelo Sibisi.

## License
This project is open-source and can be modified or distributed freely.

