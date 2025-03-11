# Nqueensproblem_202401100300255
N-Queens Problem - Randomized Hill-Climbing Solution with Random Restarts
Problem Statement
The N-Queens Problem is a classic combinatorial optimization challenge that involves placing N queens on an N×N chessboard such that no two queens threaten each other. This means:

No two queens should be in the same row, column, or diagonal.
As the value of N increases, the complexity of the problem grows significantly, making traditional brute-force methods inefficient.

Proposed Solution
This implementation leverages a randomized hill-climbing algorithm with random restarts to efficiently find a valid solution. The algorithm follows these steps:

Random Board Generation: A random starting configuration is generated with one queen placed randomly in each row.
Conflict Calculation: The algorithm calculates the number of conflicting queens.
Hill Climbing Optimization: It iteratively moves conflicted queens to positions that minimize conflicts.
Random Restarts: If no solution is found within a set number of iterations, the algorithm restarts with a new random configuration.
This method effectively handles local minima by introducing restarts, improving the chances of finding a solution for larger chessboards.

The solution is implemented in Python and includes clear visual output for easy interpretation.
