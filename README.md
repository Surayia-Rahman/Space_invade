# Space_invade


This is a simple Space Invaders game built using Python and the Pygame library. The game involves controlling a spaceship that shoots bullets to destroy enemy aliens. The game also keeps track of the player's score and ends when the enemies reach a certain point on the screen.

Features:
 1.Player Movement: The player can move left and right using arrow keys.
 2.Shooting: The player can shoot bullets by pressing the spacebar.
 3.Enemies: Multiple enemy aliens move horizontally and vertically across the screen.
 4.Collision Detection: When a bullet hits an enemy, both the enemy and the bullet disappear, and the player's score increases.
 5.Game Over: The game ends when an enemy reaches the player’s spaceship.

Requirements:
Python 3.x
Pygame library
Audio and image files for game assets (background, player, enemy, bullet, sounds)

Installation:

a. Install Python 3 from python.org.
b. Install the Pygame library
c. Download or create the required game assets
(Place all the assets and the Python script in the same directory)

 ## Game Controls:

Left Arrow: Move the spaceship left.

Right Arrow: Move the spaceship right.

Spacebar: Fire bullets at the enemies.

How to Play:

 a) Run the Python script:
   python space_invader_game.py
   
 b) Control the spaceship using the left and right arrow keys.

 c) Shoot bullets by pressing the spacebar to destroy the aliens.

The game continues until an enemy reaches the player’s spaceship, which triggers the Game Over screen.

Code Explanation:

-Pygame Setup: Initializes the game window, background, music, and icons.

-Player and Enemy Setup: Loads the images for the player and enemies, positions them, and defines the movement patterns for both.

Collision Detection: A function checks if a bullet collides with an enemy, triggering a score increment and resetting the enemy position.

-Main Game Loop: Handles user input (key presses), updates the positions of the player, enemies, and bullets, and checks for collisions. It also keeps track of the score and displays it on the screen.
