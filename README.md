Tic-Tac-Toe Game
Overview
This project is a simple command-line implementation of the classic Tic-Tac-Toe game, written in Python. The game supports both single-player (against the computer) and multiplayer modes.

Features
Single-player Mode: Play against an AI opponent.
Multiplayer Mode: Play against another human player.
Dynamic Board Display: The current state of the board is displayed after each turn.
Input Validation: Ensures that players make valid moves.
Game Outcome Analysis: Determines if there's a winner or if the game ends in a draw.
Game Rules
The game is played on a 3x3 grid.
One player is "X" and the other player (or computer) is "O".
Players take turns placing their marks in empty squares.
The first player to get 3 of their marks in a row (vertically, horizontally, or diagonally) wins.
If all 9 squares are filled and neither player has 3 in a row, the game ends in a draw.
How to Play
Starting the Game:

Run the script.
Choose between single-player mode (1) or multiplayer mode (2).
Single-player Mode:

You play as "X" and the computer plays as "O".
Choose whether to play first (1) or second (2).
Multiplayer Mode:

Two players take turns entering their moves.
Player 1 is "X" and Player 2 is "O".

Making a Move:

Enter the position (1-9) where you want to ace your mark.

Winning and Drawing:

The game checks for a winner after each move.
If there is a winner, a message is displayed indicating which player won.
If the board is full and there is no winner, the game ends in a draw.
Technical Details
Board Representation: The board is represented as a list of 9 elements.

0: Empty square
-1: "X"
1: "O"
Minimax Algorithm: The AI opponent uses the minimax algorithm to make optimal moves.

Input Handling: The script ensures that players can only place their marks on empty squares and handles invalid inputs gracefully.

Conclusion
This Tic-Tac-Toe game provides a fun and interactive way to play the classic game either against another player or an AI opponent. The implementation showcases basic game logic, board handling, and AI decision-making using the minimax algorithm. Enjoy playing!
