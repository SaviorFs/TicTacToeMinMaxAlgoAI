# Tic Tac Toe with Minimax Algorithm

This is a simple Tic Tac Toe game implemented in Java. The game includes an unbeatable AI opponent using the Minimax algorithm.

## Features

- Play Tic Tac Toe against an AI opponent.
- The AI uses the Minimax algorithm to make optimal moves.
- Simple text-based interface.

## How to Compile and Run

1. Clone the repository:
   ```bash
   git clone https://github.com/saviorfs/tic-tac-toe.git
   cd tic-tac-toe

javac src/TicTacToe.java
java -cp src TicTacToe

How to Play
Game Start:
The game starts with Player X (you) making the first move.
The board is displayed as a 3x3 grid with positions indexed from 0 to 2, where 0 represents the first row/column and 2 represents the last row/column.
Making a Move:
You will be prompted to enter your move by specifying the row and column numbers.
Enter the row number (0, 1, or 2) and press Enter.
Enter the column number (0, 1, or 2) and press Enter.
Your move will be placed on the board, and the AI (Player O) will make its move.
Game Progress:
The board will be updated and displayed after each move.
The game continues until there is a winner or the board is full (resulting in a draw).
Game End:
The game will announce the winner (Player X or Player O) or declare a draw if the board is full with no winner.
To play again, you need to re-run the game using the command java -cp src TicTacToe.

