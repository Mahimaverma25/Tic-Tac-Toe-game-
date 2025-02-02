# Tic-Tac-Toe-game

The Tic Tac Toe game is a simple, two-player game where players take turns marking spaces on a 3x3 grid. The first player to align three of their marks (either "X" or "O") in a row, column, or diagonal wins the game. If all spaces on the grid are filled without a winner, the game results in a draw.

This version of Tic Tac Toe is designed to be played in a web browser and is built using HTML, CSS, and JavaScript.

# Features
1. Two-Player Mode: Play with a friend on the same device.
 
2. Interactive Grid: Click to place either an "X" or an "O" on the board.

3. Win Detection: The game detects a winner when a player gets three marks in a row, column, or diagonal.
 
4. Draw Detection: The game ends in a draw when all the spaces are filled without a winner.
 
5. Responsive Design: The game is playable on both desktop and mobile devices.
 
# How to Play
Open the game in your browser.
Player 1 will be assigned "X" and Player 2 will be assigned "O."

Players take turns clicking on an empty square on the 3x3 grid.

The first player to align three of their marks (horizontally, vertically, or diagonally) wins.

If all squares are filled and no player has won, the game is a draw.

To restart the game, simply refresh the page.

# Game Logic
Game Board: A 3x3 grid is displayed for the players to interact with. Each square on the grid can either be empty, "X", or "O."

Player Turns: Players alternate turns. Player 1 places "X" and Player 2 places "O." The game prevents players from clicking on squares that are already occupied.

Win Condition: The game checks for three consecutive marks (either horizontally, vertically, or diagonally) after every move. If a player achieves this, they win the game.

Draw Condition: If all squares are filled and there is no winner, the game announces a draw.

Restart: The game can be reset by refreshing the page.

# Technologies Used
HTML: Used for creating the structure of the game board and interface.

CSS: Used for styling the game layout and appearance.

JavaScript: Used to handle game logic, such as checking for a winner, player turns, and rendering the game updates.


# License
This project is open-source and available under the MIT License. See the LICENSE file for more details.
