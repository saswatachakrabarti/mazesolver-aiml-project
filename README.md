# Maze Solver using AI Search Algorithms (DFS & BFS)

## Project Overview

This project implements an Artificial Intelligence based maze solving agent that finds a path from a start position (A) to a goal position (B).

The solver uses classical AI search algorithms to explore the maze and determine a valid path while avoiding obstacles.

The project also compares the performance of two algorithms:

• DFS (Depth First Search)
• BFS (Breadth First Search)

The program outputs statistics such as number of explored states, path length, and time taken to evaluate which algorithm performs better.

---

## AI Concepts Used

This project demonstrates important Artificial Intelligence concepts:

• State Space Search
• Problem Solving Agents
• Graph Traversal
• DFS (Depth First Search)
• BFS (Breadth First Search)
• Performance Evaluation of Algorithms

Maze solving is a classical AI problem similar to pathfinding in robotics, games, and navigation systems.

---

## Maze Format

The maze is provided as a text file.

Symbols used:

A → Start position
B → Goal position
# → Wall / obstacle
(space) → Walkable path

Example maze:
```

##########
#A #     #
#  # ### #
# ## #   #
#    # B #
##########
```

Rules:
• Maze must contain exactly one A (start)
• Maze must contain exactly one B (goal)
• Walls are represented using #
• Paths are represented using spaces

---

## Project Structure
```

maze-ai-solver/
│
├── mazenew.py
├── requirements.txt
├── README.md
│
├── mazes/
│   ├── maze1.txt
│   ├── maze2.txt
│   ├── maze3.txt
```

---

## Environment Setup

Make sure Python is installed.

Check Python version:

python --version

Install required dependency:

pip install -r requirements.txt

Required library:

Pillow (used to generate solution image)

---

## How to Run the Program

Run the program from the command line (terminal).

Input format:

python mazenew.py {maze_file} {algorithm}

Example:

Run BFS:

python mazenew.py mazes/maze1.txt bfs

Run DFS:

python mazenew.py mazes/maze1.txt dfs

---

## Program Output

After execution, the program will display:

• Solved maze path in terminal
• Number of states explored
• Path length
• Time taken
• Solution image saved as PNG file

Example output:

Running BFS ...

States explored: 54
Path length: 18
Time taken: 0.0021 seconds

Solution image saved as solution.png

---

## Viewing the Solution Image

After running the program, the solved maze image will be saved as:

solution.png

Open image:

Windows:

start solution.png

Mac:

open solution.png

---

## Algorithm Comparison

DFS (Depth First Search)
• Explores deeper paths first
• Uses stack data structure
• May not always give shortest path

BFS (Breadth First Search)
• Explores level by level
• Uses queue data structure
• Always finds shortest path
• Usually explores more states

The statistics printed help determine which algorithm performs better for a given maze.

---

## Learning Outcome

This project shows how Artificial Intelligence search techniques can be used to solve navigation problems efficiently.

It demonstrates how problem solving agents explore possible states and make decisions to reach a goal.

Such techniques are widely used in:

• Robotics navigation
• Video game AI
• GPS systems
• Path planning problems

---

## Author

Saswata Chakrabarti
B.Tech CSE
Fundamentals of AI and ML Project
