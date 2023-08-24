
# 10K intiative

## Overview

This is a simple command line implementation of the classic game Tic Tac Toe written in Python. The game allows two players to play against each other by placing X's and O's on a 3x3 board. The game ends when one player gets 3 in a row horizontally, vertically, or diagonally, or when the board is full with no winner.

## Getting Started

To play the game, simply run the python script `tictactoe.Ipynb`. The game board and prompts will be printed to the command line for each player to enter moves.

## Installation

No installation is required. Ensure you have Python 3 installed on your machine. Simply download the `tictactoe.Ipynb` file and run it.

## Usage

When the game starts, the empty 3x3 board will be printed. Player 1 is X and Player 2 is O. 

Players take turns entering their move in the format "row col" - for example "2 1" to place an X in the center.

The game ends when either player gets 3 in a row or the board fills up. The winner or tie game will be printed.

To play again, simply restart the Python script.

## Functionality

The core game logic is implemented in functions:

- `print_board()` to print the current state of the board
- `get_move()` to get a valid move from the current player
- `check_win()` to check if a player has won
- `check_tie()` to check if the game has ended in a tie
- `play_game()` is the main game loop, alternating players and checking for a win or tie each turn

The game state is stored in a global `board` variable, which is a 3x3 list of lists representing the squares on the board.

Input validation is implemented to handle invalid user inputs.

## Conclusion

This demonstrates a simple command line game in Python by utilizing functions, loops, input validation, and data structures like lists. Contributions and enhancements are welcome!

Let me know if you would like me to expand or modify this README further.
