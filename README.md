# Turtle Crosser

## Description
Turtle Crosser is a simple Python game built using the Turtle graphics library. The player controls a turtle character that must safely cross a busy road filled with moving cars. The objective is to reach the other side of the road without colliding with any cars.

## Features
1. **Player Control:** The player can control the turtle character using the "Up" arrow key to move upwards and "Down" arrow key to go downwards .
2. **Car Generation:** Cars are generated at the starting line and move horizontally across the screen at varying speeds.
3. **Collision Detection:** The game detects collisions between the player's turtle character and the moving cars. If a collision occurs, the game ends.
4. **Level Progression:** As the player successfully crosses the road, the game becomes progressively more challenging with increased car speed and density.
5. **Scoreboard:** Displays the current level of the game and updates as the player progresses.

## Files
1. **main.py:** The main file that initializes the game, sets up the screen, and controls the game loop.
2. **car_manager.py:** Manages the creation and movement of cars on the screen.
3. **player.py:** Defines the behavior and movement of the player's turtle character.
4. **scoreboard.py:** Manages the scoreboard and level progression.
5. **README.md:** A file containing information about the project, how to run it, and any other relevant details.

## Dependencies
1. Turtle graphics library
2. Plyer library for sound effects (optional)

## Installation
1. Ensure Python is installed on your system.
2. Install the required libraries using pip:
```
pip install plyer
```

## How to Run
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run the main.py file using Python:
```
python main.py
```

## Controls
- Use the "Up" arrow key to move the turtle character upwards.
- Use the "Down" arrow key to move the turtle character downwards.


## Acknowledgments
- Inspiration for this project came from classic arcade games like Frogger.
