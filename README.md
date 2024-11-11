# Depth-First-Search-DFS-Maze-Solver
# Overview
This Python script implements the Depth First Search (DFS) algorithm to solve a maze using the Turtle graphics library. The program visually represents the maze and the search process, allowing users to observe how DFS explores paths to find a solution.

# Key Components
1. Turtle Graphics Setup
The script creates a Turtle graphics window where the maze is displayed.
The window has a black background and is titled "A Maze Solving Program."
2. Maze Representation
The maze is defined using a grid of characters:
+ represents walls.
  (space) represents paths.
s marks the start position.
e marks the end position.
3. Turtle Classes
Five turtle classes are defined to represent different elements of the maze:
Maze (white turtle): Used to stamp the walls of the maze.
Green turtle: Marks the cells that have been visited during the search.
Blue turtle: Shows the frontier cells currently being explored.
Red turtle: Indicates the starting position.
Yellow turtle: Represents the end position and the solution path.
4. Maze Setup Function
The setup_maze function initializes the maze based on the provided grid:
It iterates through each character in the grid, determining the position of walls, paths, the start, and the end points.
Turtles are moved to their respective positions and stamped to visualize the maze layout.
5. DFS Search Function
The search function implements the DFS algorithm:
It uses a frontier list to keep track of the current path being explored.
The algorithm explores possible moves (up, down, left, right) and marks cells as visited.
If a cell is part of the path and has not been visited, it is added to the frontier.
The algorithm continues until the end position is reached.
6. Backtracking to Find the Solution Path
The backRoute function is called once the end is reached:
It retraces the path from the end back to the start, marking the solution path with the yellow turtle.
7. Execution Flow
The maze is set up, the DFS search is performed, and the solution path is visualized.
The program ends when the user clicks on the Turtle graphics window.
# Conclusion
This script serves as an educational tool for understanding how the Depth First Search algorithm works in the context of maze solving. The visual representation through Turtle graphics makes it engaging and helps illustrate the algorithm's process of exploration and backtracking. Users can modify the grid to test different maze configurations, enhancing their understanding of DFS.

