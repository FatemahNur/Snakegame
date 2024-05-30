# Snake Game
This is a simple Snake game implemented in Java using the Swing library for the graphical user interface. The game allows you to control a snake, eat apples to grow in length, and try to avoid collisions with the walls or the snake's own body.

# Features
Classic Snake gameplay
Smooth animations and controls
Score tracking

# Restart functionality
Game over screen with score display

# How to Play
Use the arrow keys to control the direction of the snake.
Eat apples to grow in length and increase your score.
Avoid colliding with the walls or the snake's own body.
Press Enter to restart the game after a game over.

# Controls
Left Arrow Key: Move left
Right Arrow Key: Move right
Up Arrow Key: Move up
Down Arrow Key: Move down
Enter Key: Restart the game after a game over

# Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/snake-game.git
Navigate to the project directory:
bash
Copy code
cd snake-game
Compile the Java files:
bash
Copy code
javac SnakeGame.java
Run the game:
bash
Copy code
java SnakeGame

# Code Overview
The main game logic is implemented in the SnakeGame class, which extends JFrame and implements ActionListener. Here's a brief overview of the key methods:

SnakeGame(): Constructor that sets up the game window and starts the game.
startGame(): Initializes the game state and starts the game timer.
initSnake(): Initializes the snake with a default length and position.
newApple(): Generates a new apple at a random position.
move(): Updates the snake's position based on the current direction.
checkApple(): Checks if the snake has eaten an apple and updates the game state accordingly.
checkCollisions(): Checks for collisions with the walls or the snake's own body.
gameOver(Graphics g): Displays the game over screen with the final score.
actionPerformed(ActionEvent e): Handles timer events to update the game state and repaint the screen.
restartGame(): Restarts the game with the initial state.
MyKeyAdapter: Inner class that handles key events for controlling the snake.

# Contributing
Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.

# License
This project is licensed under the MIT License. See the LICENSE file for details.

# Acknowledgements
This project was inspired by the classic Snake game.
The game logic and GUI are implemented using Java Swing.


Enjoy playing the Snake game!
