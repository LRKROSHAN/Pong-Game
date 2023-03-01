# Pong-Game
# 2 D Game Engine Construction
# GAME DOCUMENT FOR PONG GAME 
# ROSHANKUMAR LOGANATHAN

GAME IMAGE :


PROGRAM VERSION :

OS Version		  :	macOS Ventura Version 13.0.1
Python Version	:	3.9.6
Pygame Version	:	2.1.2

MOTIVATION : I chose to build a game on pong since it is a simple game with straightforward game mechanics and is a great introduction to game development.
This allows me to learn the basics of game design and improvise in furture projects. The game pong also has a nostalgic appeal to it since i used to play this game during my childhood in my old television.

REASONING : The game sets up the game window, defines the Paddle and Ball classes, and includes functions for drawing the game elements, handling collisions, and updating the game state. The main game loop handles user input and updates the game state accordingly. I chose to go with this sequential approach since it would be easier to keep the classes, functions and elements in check and make changes with ease.

IMAGE : 

The Paddle class represents the player-controlled paddles on either side of the screen. 

The Ball class represents the ball that moves between the paddles.

The draw() function handles drawing all the game elements to the screen, including the paddles, ball, and score.

The handle_collision() function checks for collisions between the ball and the paddles or the top and bottom of the screen, and updates the ball's velocity accordingly.

The handle_paddle_movement() function handles moving the paddles up and down based on user input.

The main() function initializes the game and sets up the main game loop. The loop checks for user input and updates the game state accordingly, including moving the paddles and ball, checking for collisions, and updating the score. The game ends when one player reaches the winning score.

FUTURE WORK :


