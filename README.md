# Tic Tac Toe Game in C++

## Introduction

This repository contains two implementations of the classic Tic Tac Toe game in C++. The first implementation is a simple console-based version, and the second implementation follows the Object-Oriented Programming (OOP) paradigm. The games allow two players to take turns marking spaces on a 3x3 grid until a player wins or the game ends in a draw.

## Console-Based Tic Tac Toe (Non-OOP)

### Files
- **tictactoe.cpp**: Contains the source code for the console-based Tic Tac Toe game.
  
### How to Play
1. Compile the source code using a C++ compiler (e.g., g++).
   ```bash
   g++ tictactoe.cpp -o tictactoe
   ```
2. Run the executable.
   ```bash
   ./tictactoe
   ```
3. Follow the on-screen instructions to play the game.

## Object-Oriented Tic Tac Toe (OOP)

### Files
- **tictactoe_oop.cpp**: Contains the source code for the OOP version of the Tic Tac Toe game.
  
### How to Play
1. Compile the source code using a C++ compiler (e.g., g++).
   ```bash
   g++ tictactoe_oop.cpp -o tictactoe_oop
   ```
2. Run the executable.
   ```bash
   ./tictactoe_oop
   ```
3. Follow the on-screen instructions to play the game.

## Object-Oriented Design

The OOP version uses two classes: `base` and `derived`. The `base` class contains methods for drawing the game board and checking for a draw. The `derived` class inherits from the `base` class and adds a method for getting player moves. The game is played by creating an instance of the `derived` class and calling its methods in a loop until the game ends.

Feel free to explore and modify the code to suit your needs or enhance the game features.

Enjoy playing Tic Tac Toe!