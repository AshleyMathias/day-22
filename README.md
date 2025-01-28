# day-22
Pong Game 🎮
A classic implementation of the retro Pong game using Python's turtle module. This game is designed for two players and features smooth gameplay, collision mechanics, and a scoring system.

Features
Two-Player Gameplay: Compete with a friend using separate controls.
Collision Detection: Ball bounces off walls and paddles.
Score Tracking: Keeps track of each player's score with real-time updates.
Game Reset: Ball resets position after scoring.
Smooth Animations: Achieved using tracer for seamless movement.
How to Play
Run the Game:

Clone this repository or download the files to your local machine.
Ensure you have Python installed (version 3.6 or later).
Run the main script:
bash
Copy
Edit
python main.py
Controls:

Right Paddle:
Move Up: Press the Up Arrow key.
Move Down: Press the Down Arrow key.
Left Paddle:
Move Up: Press the W key.
Move Down: Press the S key.
Objective:

Prevent the ball from passing your paddle to score points.
The first player to reach the winning score (default: unlimited) wins.
Code Structure
main.py: The main game logic, initializes the game window and manages interactions.
paddle.py: Contains the Paddle class for controlling paddle movement.
ball.py: Contains the Ball class for ball behavior, including movement, bouncing, and resetting.
scoreboard.py: Contains the Scoreboard class to track and display scores.
Requirements
Python 3.6+
Turtle graphics module (pre-installed with Python).
