# Tic-Tac-Toe (Pygame)

Overview
This is a simple Tic-Tac-Toe game implemented in Python using the Tkinter library. The game provides a graphical user interface (GUI) where two players take turns marking spaces in a 3x3 grid with "X" or "O". The first player to align three symbols horizontally, vertically, or diagonally wins the game.
Features

Interactive GUI: A 3x3 grid of buttons for gameplay.
Player Turns: Alternates between players "X" and "O".
Winner Detection: Automatically checks for a winner after each move.
Visual Feedback: Highlights winning combination in green.
Game End: Displays a message box announcing the winner and closes the game.

Prerequisites

Python 3.6+
Tkinter (included with standard Python installations)

Installation

Clone the Repository:
git clone <repository-url>
cd tic-tac-toe


Run the Application:No additional dependencies are required since Tkinter is part of Python's standard library.
python tic_tac_toe.py



Usage

Launch the script to open the Tic-Tac-Toe window.
Players take turns clicking empty buttons to place their symbol ("X" or "O").
The current player's turn is displayed at the bottom of the window.
When a player wins, the winning line is highlighted in green, a message box announces the winner, and the game closes.
If no winner is determined, continue playing until a win occurs or the grid is full.

Code Structure

Main Components:
check_winner(): Checks for a winning combination after each move.
button_click(index): Handles button clicks, updates the grid, and triggers winner checks.
toggle_player(): Switches the current player between "X" and "O".


GUI Setup:
Uses Tkinter to create a 3x3 grid of buttons.
A label displays the current player's turn.
Messagebox for winner announcement.



Notes

The game does not include a draw condition; it continues until a winner is found or the user closes the window.
The game window closes automatically after a win.
The button grid is non-resizable for simplicity.

License
This project is licensed under the MIT License. See the LICENSE file for details.
Contributing
Contributions are welcome! Please submit a pull request or open an issue for suggestions or bug reports.
