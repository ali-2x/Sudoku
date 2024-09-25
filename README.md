# Sudoku Game
This repository contains a Sudoku game implemented in Java.
The goal of the game is to solve a classic 9x9 Sudoku puzzle where:
* Each row must contain the digits 1 to 9 without repetition.
* Each column must also contain the digits 1 to 9 without repetition.
* Each of the nine 3x3 sub-grids (or boxes) must contain the digits 1 to 9 exactly once.

**Features**
Grid Initialization: The game starts with a partially filled 9x9 grid with some given digits.
Unique Solution: Each puzzle generated or given to the game has a unique solution.
Interactive Play: Players can attempt to solve the puzzle by filling in the missing numbers.
Error Detection: The game checks if the player's solution violates Sudoku rules

Compile the code: javac Sudoku.java
Run the game: java Sudoku

**How to Play**
The game presents a partially filled 9x9 grid.
Players input numbers to fill the empty cells.
The game validates the player's solution, ensuring that all rows, columns, and 3x3 boxes contain each number from 1 to 9 exactly once.

**Acknowledgments**

This project was developed as part of a programming assignment for the course - Problem Solving using Object Oriented Programming in Java.
Designed By: Dr. Kevin Wang, Lecturer at HKBU Computer Science Department
