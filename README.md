# Tic Tac Toe Game

Welcome to the **Tic Tac Toe Game** repository! This is a simple implementation of the classic Tic Tac Toe game that you can play in the terminal or with a graphical interface depending on the implementation you choose.

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [How to Play](#how-to-play)
- [Contributing](#contributing)
- [License](#license)

## Description

Tic Tac Toe is a two-player game where each player takes turns marking a square on a 3x3 grid with either an 'X' or an 'O'. The objective is to be the first to get three of their marks in a row, either horizontally, vertically, or diagonally. This repository contains a basic version of the game, which can be played either in a terminal/console window or via a graphical user interface, depending on the implementation.

## Features

- Play the game between two players (Player vs Player)
- The game can be played in the terminal or a graphical interface (depending on the version)
- It checks for a winner or a draw after each turn
- Easy-to-understand code for anyone to modify or improve
- Support for different board sizes and rules in future versions


## Installation

1. **Clone the repository:**

   First, clone this repository to your local machine.

   ```bash
   https://github.com/its-anamika-anand/Tic-Tac-Toe.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd Tic-Tac-Toe
   ```

3. **Install dependencies (for GUI version):**

   If you are running a GUI version (using `tkinter` or `pygame`), ensure you have the required libraries. For example:

   - `tkinter` usually comes pre-installed with Python.
   - For `pygame`, run:

   ```bash
   pip install pygame
   ```

   No dependencies are required for the terminal-based version.

## Usage

- **For the terminal-based version:**

   To play the game in the terminal, simply run the following command:

   ```bash
   python tic_tac_toe.py
   ```

   Follow the on-screen instructions to make your moves by entering the row and column numbers.

- **For the GUI-based version:**

   If you've chosen a graphical user interface implementation, run the game using:

   ```bash
   python gui_tic_tac_toe.py
   ```

   The game will open a window with the board, where players can click on the grid to make their moves.

## How to Play

1. The game is played on a 3x3 grid.
2. Player 1 will use 'X' and Player 2 will use 'O'.
3. Players take turns marking their spots on the grid.
4. The first player to get three marks in a row (horizontally, vertically, or diagonally) wins.
5. If all spots are filled and no player has won, the game results in a draw.

## Contributing

We welcome contributions to improve the game! Here are some ways you can help:

- Reporting bugs or issues
- Suggesting new features
- Improving documentation
- Submitting pull requests



Enjoy playing the game! Feel free to enhance it further or adapt it for your own needs. If you have any questions or suggestions, open an issue or reach out!
