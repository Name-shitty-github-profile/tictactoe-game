# Terminal-based Tic-Tac-Toe Game

A classic game of Tic-Tac-Toe that you can play in your terminal. The game is implemented in C and provides a simple and interactive way to enjoy this timeless game.

## How to Play

1. Make sure you have a C compiler installed on your system.<br>
2. Compile the provided C code using the C compiler.<br>
3. Run the compiled executable to start the game.<br>
4. Follow the on-screen instructions to make your moves and enjoy the game!

## Prerequisites

- C Compiler (e.g., GCC)

## Installation

1. Clone this repository or download the provided C code file (`tictactoe.c`).<br>
2. Open your terminal and navigate to the directory containing the downloaded `tictactoe.c` file.<br>
3. Compile the code using the following command:

```bash
   gcc -o tictactoe tictactoe.c
```
## Usage
Run the compiled executable:
```bash
./tictactoe
```
The game will prompt you to enter your moves as row and column coordinates (both in the range of 0 to 2). Players will take turns to make their moves.
<br>
The game will display the current state of the board after each move.
<br>
The game ends when a player wins or the game is a draw. The final result will be displayed, and the game will exit.

# Game Rules
The game is played on a 3x3 grid.
Players take turns to place their symbols ('X' or 'O') on the grid.
The objective is to form a horizontal, vertical, or diagonal line of three of your symbols.
If all cells are filled and no player has won, the game is a draw.
# License
This project is licensed under the MIT License.
