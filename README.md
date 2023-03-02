# Pong-Game
# 2 D Game Engine Construction
# GAME DOCUMENT FOR PONG GAME 
# ROSHANKUMAR LOGANATHAN

**GAME IMAGE :**


**PROGRAM VERSION :**

OS Version		  :	macOS Ventura Version 13.0.1
Python Version	:	3.9.6
Pygame Version	:	2.1.2

**MOTIVATION :**
  I chose to build a game on pong since it is a simple game with straightforward game mechanics and is a great introduction to game development.
This allows me to learn the basics of game design and improvise in furture projects. The game pong also has a nostalgic appeal to it since i used to play this game during my childhood in my old television.

**REASONING :**
  The game sets up the game window, defines the Paddle and Ball classes, and includes functions for drawing the game elements, handling collisions, and updating the game state. The main game loop handles user input and updates the game state accordingly. I chose to go with this sequential approach since it would be easier to keep the classes, functions and elements in check and make changes with ease.

**IMAGE :** 
  The relationships between the classes, functions, and variables in this code can be viewed using the given Miro Link:
https://miro.com/app/board/uXjVPNtajwk=/?share_link_id=600101440238


The Paddle class represents the player-controlled paddles on either side of the screen. 

The Ball class represents the ball that moves between the paddles.

The draw() function handles drawing all the game elements to the screen, including the paddles, ball, and score.

The handle_collision() function checks for collisions between the ball and the paddles or the top and bottom of the screen, and updates the ball's velocity accordingly.

The handle_paddle_movement() function handles moving the paddles up and down based on user input.

The main() function initializes the game and sets up the main game loop. The loop checks for user input and updates the game state accordingly, including moving the paddles and ball, checking for collisions, and updating the score. The game ends when one player reaches the winning score.

**FUTURE WORK :**
The following can be done inorder to improvise the game in the future.

AI opponents: Implement an AI system as the opponent player to make the game more challenging for the player.

Power-ups: Add power-ups to the game that can provide temporary benefits or advantages to the player, such as a larger paddle, reduce the speed of opponent, faster ball speed, etc.

User Experience: Improvide the user experience by adding a menu, including different difficulties, introduce in-game music, etc.

Obstacles: You can introduce obstacles in the game, such as walls, blocks, or moving barriers that can make the game more challenging.

**Generalization:**
Although pong is a simple game we could learn and implement its core mechanics can be applied to a wide range of other games and applications.
Pong's basic gameplay mechanics can be applied to various sports games like tennis, table tennis, soccer or badminton since the primary objective of these games is to hit the ball back and forth while trying to score points.

