# Suddoku_Game
This project implements a backtracking-based Sudoku solver in C++. It takes a 9x9 Sudoku grid with some pre-filled numbers (and zeros representing empty cells), and recursively fills in the grid by checking the safety of each digit placement according to Sudoku rules.

💡 Features:
Solves any valid 9x9 Sudoku puzzle using backtracking.

Checks for safe placement of digits in rows, columns, and 3x3 subgrids.

Prints the solved Sudoku grid, if a solution exists.

🧮 Algorithm Used:
Backtracking: Try placing digits from 1 to 9 in each empty cell, backtrack if constraints are violated.

Input Board:

<img width="407" height="277" alt="image" src="https://github.com/user-attachments/assets/c894ab49-31db-4a5f-8829-3da78a04b5a0" />

Output:

<img width="550" height="346" alt="image" src="https://github.com/user-attachments/assets/3a843410-f15d-43ca-b517-9d7c8a48fb67" />

