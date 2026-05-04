# python-snake-game
A classic Snake game built in Python using object-oriented programming principles.

## Description
This is a simple implementation of the classic Snake game using Python's built-in `turtle` graphics library. The game features a snake that moves around the screen, eating food to grow longer while avoiding collisions with the walls or its own body. The objective is to achieve the highest score possible before the game ends.

## Features
- **Snake Movement**: Control the snake using arrow keys (Up, Down, Left, Right).
- **Food Consumption**: The snake grows longer each time it eats food.
- **Score Tracking**: Keep track of your score as you eat more food.
- **Collision Detection**: Game ends if the snake hits the wall or its own tail.
- **Game Over Screen**: Displays "Game Over" when the game ends.

## Project Structure
- `main.py`: The main game loop and setup.
- `snake.py`: Defines the Snake class, handling movement, growth, and segments.
- `food.py`: Defines the Food class, responsible for placing food on the screen.
- `scoreboard.py`: Defines the Scoreboard class, managing score display and game over messages.
- `LICENSE`: The license file for the project.
- `README.md`: This file.

## How to Run the Game
1. Ensure you have Python installed on your system (version 3.x recommended).
2. Clone or download this repository to your local machine.
3. Navigate to the project directory in your terminal or command prompt.
4. Run the game using the following command:
   ```
   python main.py
   ```
5. Use the arrow keys to control the snake.
6. The game will start in a new window. Enjoy!

## Requirements
- Python 3.x
- No external libraries required (uses built-in `turtle` module).

## Controls
- **Up Arrow**: Move snake up
- **Down Arrow**: Move snake down
- **Left Arrow**: Move snake left
- **Right Arrow**: Move snake right

## Game Rules
- Eat the food (red circle) to grow and increase your score.
- Avoid hitting the walls (edges of the screen).
- Avoid colliding with your own tail.
- The game ends when you hit a wall or your tail.
- Try to get the highest score possible!

## Contributing
Feel free to fork this repository and submit pull requests for improvements or bug fixes.

## License
This project is licensed under the terms specified in the LICENSE file.
