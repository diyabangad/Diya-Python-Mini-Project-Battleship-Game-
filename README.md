Battleship Game
Welcome to the Battleship Game project! This is a classic implementation of the Battleship game in Python, where players attempt to sink each other's fleet of ships by guessing their locations on a grid.

Features:
Single-Player Mode: Play against a simple AI that randomly places and guesses ship locations.
Grid-Based Gameplay: A a user customizable grid where ships are be placed in cells using Random Function.
Interactive Command-Line Interface: Users input their guesses through the command line and receive feedback.

Functions Used:
1)	Append: It adds a single item to the given list.
2)	Define:  def is the keyword for defining a function. The function name is followed by parameter(s) in ().
	create_grid(): creates the 2D data grid in the form of lists of rows and columns
	display_grid(): displays the created grid with letters for column names and numbers for the row names
	random_row(): generates a random row integer
	random_column(): generates a random column integer
	update_gridHit(): if the ship is hit, replaces the cell in the grid with ‘O’
	update_gridMiss(): if the ship is not hit, replaces the cell in the grid with ‘X’
3)	Import Random: randint() is an inbuilt function of the random module in Python, used to generate a random number.
Random.radint() generates a random integer between 1 to 9 as coordinates to place the ship.
4)	Loops (For and While)
5)	Range function

Acknowledgments:
Thanks to the Python community for their excellent tutorials and resources.

