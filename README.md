# Sudoko
Project Overview:

This project is a Python-based solution to solve Sudoku puzzles using the Backtracking algorithm. Sudoku is a popular number puzzle, and solving it computationally requires logical deduction and constraint satisfaction. The goal of the project is to fill a 9x9 grid so that each column, row, and 3x3 subgrid contains all digits from 1 to 9 without repetition.

Key Features:

Backtracking Algorithm: The program uses a recursive backtracking approach to explore different number placements. If a number doesn’t lead to a solution, the algorithm backtracks and tries a different number.
Efficiency: It checks for valid number placements by ensuring that the current number doesn’t violate Sudoku’s rules before proceeding.
User Input: The Sudoku puzzle is entered as a partially filled grid, and the program returns the completed solution.
Error Handling: If the given puzzle is unsolvable, the program gracefully exits with a relevant message.

Skills & Technologies:

Programming Language: Python
Algorithm Design: Implemented the backtracking technique to solve constraint satisfaction problems efficiently.
Problem Solving: Tackled a classic algorithmic problem, understanding its constraints and systematically applying recursive solutions.
