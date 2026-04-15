# Sudoku CSP Solver (AC-3 + Backtracking + Forward Checking)

This project implements a **Constraint Satisfaction Problem (CSP) based Sudoku Solver** using:
- Backtracking Search
- Forward Checking
- AC-3 (Arc Consistency Algorithm)

It solves Sudoku puzzles of different difficulty levels and also tracks search performance.


##  Features

- Solves standard 9×9 Sudoku puzzles
- Uses CSP techniques for efficient solving
- Implements:
  - AC-3 for constraint propagation
  - Forward Checking for pruning domains
  - Backtracking search for exploration
- Tracks:
  - Number of backtracking calls
  - Number of failures


## Input Format

Each Sudoku puzzle is stored in a `.txt` file:

- Exactly **9 lines**
- Each line contains **9 digits (0–9)**
- `0` represents an empty cell

### Example:
004030050
609400000
005100489
000060930
300807002
026040000
453009600
000004705
090050200

---

## Algorithms Used

### 1. AC-3 (Arc Consistency)
Reduces variable domains by enforcing consistency between cells.

### 2. Forward Checking
Removes invalid values from neighbors after assignments.

### 3. Backtracking Search
Explores possible assignments when inference is not enough.

##  How to Run
ai_ass5_23f0805_6d.ipynb
