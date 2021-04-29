# sodukosolver

This Python module can solve Sodoku problems. 

**HOW TO SOVLE**

import solver
import boards

board = solver.solve(boards.board_hard)

To solve a different problem, pass in the board you want to solve to the constructor of the SudokuBoard.

The Board should be a list of 9 strings of length 9.

Each entry represents a square on the board.

Use 0 for blanks. 

Whitespaces will be stripped, and can be added to the strings for readability.

See boards.py for example boards.
