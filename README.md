# sodukosolver21

This python query can solve Sodoku Puzzles. Please note, you are able to use the Sudokusolver21 with any text file.

If you would like python to generate random puzzles for you, please use the query:

  python3 Generator.py

You will be prompted with the following questions:
  1. How many Sudoku puzzles would you like to generate?: 
  2. Easy or Difficult puzzles?: (e or d)

Generator.py creates SudokuPuzzles.txt file.

Each puzzle is represented as a single line of (81) integers; '0' values are null.

Alternatively, you can use your own number sequence; this can be represented by a single line or grid format.

A grid is 81 interger where read by first row, left to right (A1 - A9); repeat for second row, left to right (B1 - B9); ... repeat for ninth row, left to right (I1 - I9); A1 - I9.

If you would like python to solve the SudokuPuzzles.txt contained, please use this query:

  python3 pysudoku.py SudokuPuzzles.txt
  
Happy Solving :)
