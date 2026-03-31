# Maze Solver using AI Search Algorithms (DFS & BFS)

## Project Overview

This project is designed to develop an Artificial Intelligence-based maze solver agent to find the path between the start point (A) and the end point (B).

This maze solver agent will utilize the classical search algorithms used in Artificial Intelligence to search the maze and find a path to the goal point while avoiding obstacles.

This project is also designed to compare the performance of two search algorithms:

• DFS (Depth First Search)
• BFS (Breadth First Search)

This program will display the statistics to determine which algorithm performs better.
---

## AI Concepts Used

This project is used to demontrate important Artificial Intelligence concepts:

• Problem Solving Agents
• Graph Traversing
• DFS (Depth First Search)
• BFS (Breadth First Search)
• Performance Evaluation of Algos


---

## Why I chose this project?
I selected the problem of solving a maze because I believe it is a great representation of how AI search algorithms work in real-life navigation problems. I thought that, as a Computer Science student, it was interesting to see how different algorithms explore the same problem in different ways.

---


## Maze Format

The maze is provided as a text file.

Symbols used:

A → Start position
B → Goal position
```# → Wall / obstacle```
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
│
└── output/
    ├── maze1_bfs.png
    ├── maze1_dfs.png
    ├── maze2_bfs.png
    ├── maze2_dfs.png
    ├── maze3_bfs.png
    ├── maze3_dfs.png
```

---

## Environment Setup

Make sure Python is installed and check python version

python --version

Installing required dependency:

pip install -r requirements.txt

Required library:

Pillow (used to generate solution image)

---

## How to Run the Program

Run the program from the command line.

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
• Searches deeper before moving to the next level
• Uses a stack data structure
• Does not guarantee the shortest path

BFS (Breadth First Search)
• Searches level by level
• Uses a queue data structure
• Guarantees the shortest path
• Searches more states

The statistics printed will help determine which algorithm performs better for a given maze.

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
