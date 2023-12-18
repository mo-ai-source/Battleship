# Battleship Game in Python with Tkinter
This repository contains a Python implementation of the classic game Battleship, with a graphical user interface (GUI) created using Tkinter. The game features a player vs. AI mode, where the player can compete against a simple AI opponent. The AI can place ships automatically, make random attacks, and follow up on hits.

# Features
- Graphical representation of the Battleship game using Tkinter.
- Player vs. AI gameplay.
- Automatic ship placement for AI.
- Ability to manually place player's ships.
- Gameplay logic including attacking, hit detection, and sinking ships.
- End game detection when all ships of a player are sunk.
# Requirements
Python 3.x
Tkinter library (usually comes pre-installed with Python).

# Installation
Clone or download the repository to your local machine.
Ensure Python 3.x is installed on your system.

# Running the Game
To run the game, navigate to the directory containing the battleship.py file in your terminal or command prompt, and then execute:
```
python battleship.py
```
# How to Play
- Start the game. A window will open with two boards: the player's board and the AI's board.
- Place your ships on the player's board. You can choose the ship to place and its orientation (horizontal or vertical).
- Once all ships are placed, the game starts.
- Click on the AI's board to make an attack.
- The game alternates turns between the player and the AI.
- Hits, misses, and sunk ships will be indicated on the boards.
- The game ends when all ships of either player are sunk.
- A prompt will ask if you want to play again at the end of the game.

# Game Components
- BattleshipGUI: Main class for handling the GUI elements and game interactions.
- Ship: Represents a ship with its size and coordinates.
- Board: Represents the game board with ship placements and attacks.
- Player: Handles player actions and board state.
- AIPlayer: Inherits from Player, adds AI capabilities for ship placement and attacking.
- Game: Manages the overall game state.
# Contributing
Contributions, issues, and feature requests are welcome. Feel free to check issues page if you want to contribute.

# License
Distributed under the MIT License. See LICENSE for more information.

Contact
Mohamed Yusuf - @mowhy01

Project Link: https://github.com/mo-ai-source/battleship

# Acknowledgments
- Tkinter Documentation
- Python Official Documentation

