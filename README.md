# 8-Puzzle Solver using BFS and DFS
This project contains a Python implementation of the 8-Puzzle Problem using Breadth-First Search (BFS) and Depth-First Search (DFS) algorithms. It demonstrates how these two uninformed search methods solve the puzzle and evaluates their performance in terms of the number of steps and memory usage.

# 📂 File Included

AI_Assignment_01_8_Puzzle.ipynb:
Jupyter Notebook implementing BFS and DFS for solving the 8-puzzle problem, including visualization of intermediate steps and comparisons of the number of steps each algorithm takes to reach the goal.

# 🧩 Problem Description
The 8-Puzzle Problem is a sliding puzzle consisting of 8 numbered tiles and a blank space (B) arranged on a 3x3 grid. The objective is to move the tiles to reach the goal configuration:

Initial State:

css
Copy
Edit
1 3 4
2 B 5
8 6 7
Goal State:

css
Copy
Edit
1 2 3
4 5 6
7 8 B

# 📌 Algorithms Implemented

# 1. Breadth-First Search (BFS)
Explores all nodes at the current depth before moving deeper.
Guaranteed to find the shortest path (if all edge costs are equal).
High memory usage as it must store all nodes at each level.

# 3. Depth-First Search (DFS)
Explores as deep as possible along one path before backtracking.
More memory-efficient than BFS.
Not guaranteed to find the shortest path.

# 🔧 How to Run
Clone the repository to your local machine:
bash
Copy
Edit
git clone <repository-url>
Open AI_Assignment_01_8_Puzzle.ipynb in Jupyter Notebook or any compatible environment.
Execute the cells to run BFS and DFS and view their output.

# 📈 Outputs
Displays each state of the puzzle as BFS and DFS explore possible moves.
Reports the number of steps taken by each algorithm to reach the goal state.
# 📊 Comparison of BFS and DFS Performance
BFS:
Finds the shortest path but consumes significant memory.
DFS:
Uses less memory but may not find the shortest path in some cases.
# ✍️ Authors
Manjul Mayank (IIT Patna, AI & Data Science)
