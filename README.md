# sodukosolver

This Python query can solve Sodoku puzzles. 

--Run Query--
solver:
python pysudoku.py Sudokus.txt

Generator:
python Generator.py

Please note, you are able to use the solver with any text file that contains Sudoku puzzles.
The generator writes to a file named "SudokuPuzzles.txt".
Each puzzle is represented as a single line of integers.
Read grid by first row, left to right (A1 - A9); repeat for second row, left to right (B1 - B9); ... repeat for ninth row, left to right (I1 - I9).
