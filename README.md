# Flappy-Bird

Flappy Bird is a popular mobile game that was released in 2013 by Vietnamese developer Dong Nguyen. In the game, the player controls a bird that must navigate through a series of pipes by flapping its wings to fly upwards and avoid obstacles.

## Instructions to run the game

* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type ```python flappy.py``` and press Enter to start the game.

* Follow the prompts to play the game.

## Functionality of the code

* The first section of the code contains the necessary import statements for various modules used in the code such as ```math```, ```os```, and ```Pygame```.
* Several constants are defined next, including the ```frames per second (FPS)```, the ```speed of the bird's animation```, the ```width and height of the window```, etc.
* The ```Bird class``` is defined with several methods and attributes. It represents the bird character controlled by the player.
* The ```PipePair class``` is defined next. It represents an obstacle in the game that consists of a top and a bottom pipe.
* The ```main() function``` is defined next. This is where the game loop is implemented. It listens for user input, updates the game state, and draws the graphics.
* In the ```main() function```, the Pygame library is initialized, the game window is created, and the background image is loaded.
* A Bird instance is created, and the pipes are generated using the ```PipePair class```.
* The game loop begins, which listens for user input and performs the game's logic, such as updating the bird's position and checking for collisions with the pipes.
* The game loop also draws the graphics on the screen, including the bird, the pipes, and the score.
* The game loop continues until the player loses by hitting a pipe, at which point the loop is exited, and the game is over.
