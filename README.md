# Vacuum Cleaner Pathfinding Simulation

This project simulates a **vacuum cleaner agent** navigating a grid environment to clean dirty spots using various **pathfinding algorithms**, including **A\*** (_Manhattan & Euclidean_), **Greedy Search**, **BFS**, **DFS**, **UCS**, and custom movement heuristics like **StayLeft** and **StayUp**. The goal is to analyze how these algorithms impact efficiency in terms of **nodes explored, path length, and execution time**.

## Overview

This project is a **Python-based simulation** where an autonomous vacuum cleaner moves through a grid to clean dirt. The vacuum cleaner follows an optimal path determined by different **search algorithms**, each affecting the agent's **efficiency and movement strategy**:

- **A\* (Manhattan & Euclidean Heuristics)**: Evaluates paths using cost functions to optimize movement.
- **Greedy Best-First Search**: Prioritizes movement toward the goal but may ignore optimal paths.
- **Breadth-First Search (BFS)**: Expands nodes evenly layer by layer, ensuring shortest paths for uniform-cost scenarios.
- **Depth-First Search (DFS)**: Explores as deep as possible before backtracking, which may result in suboptimal paths.
- **Uniform-Cost Search (UCS)**: Expands the lowest-cost node first, ensuring optimality for varying path costs.
- **StayLeft & StayUp Movement**: Custom heuristics where the vacuum prioritizes moving left or up when paths are ambiguous.

## Features

✔ Implements **A\*** algorithm with **Manhattan** and **Euclidean** heuristics.  
✔ Adds multiple search strategies: **Greedy Search, BFS, DFS, UCS, StayLeft, StayUp**.  
✔ Compares path efficiency in terms of **nodes explored** and **path cost**.  
✔ Visualizes the **grid and vacuum cleaner movement**.  
✔ Allows customization of **grid size** and **dirt placement**.
