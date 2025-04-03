**Optimization and Pathfinding Algorithms**

This repository contains Jupyter Notebook implementations of various optimization and pathfinding algorithms, including Simulated Annealing, Hill Climbing, Branch & Bound, and Iterative Deepening A*. These algorithms are applied to problems such as the Traveling Salesman Problem (TSP), Ant Maze Navigation, and the Frozen Lake problem.

**Contents**
1. Traveling Salesman Problem (TSP)
  TSP SA.ipynb → Solves TSP using Simulated Annealing.

  TSP HC.ipynb → Solves TSP using Hill Climbing.

2. Ant Maze Navigation
  ANTMAZE IDA_.ipynb → Solves Ant Maze using Iterative Deepening A*.

  ANTMAZE B&B.ipynb → Solves Ant Maze using Branch & Bound.

3. Frozen Lake Problem
  Frozen Lake IDA_.ipynb → Solves Frozen Lake using Iterative Deepening A*.

  Frozen Lake B&B.ipynb → Solves Frozen Lake using Branch & Bound.

## Requirements
Ensure you have the following Python libraries installed:

pip install numpy matplotlib networkx gym

**Descriptions of the Algorithms**
1. Simulated Annealing (SA)
  A probabilistic technique for approximating the global optimum of a function.

  Applied to TSP to find a near-optimal tour.

2. Hill Climbing (HC)
  A local search algorithm that iteratively moves towards higher-valued states.

  Used for TSP to find a shorter route.

3. Iterative Deepening A (IDA*)
  A search algorithm that finds the shortest path in an incremental depth-limited manner.

  Used for Ant Maze and Frozen Lake navigation.

4. Branch & Bound (B&B)
  A systematic method for solving optimization problems by pruning suboptimal solutions.

  Applied to Ant Maze and Frozen Lake for efficient pathfinding.

**Usage and Applications**
Traveling Salesman Problem (TSP): Find the shortest path connecting multiple cities.

  Ant Maze Navigation: Simulates an ant finding the shortest path through a maze.

Frozen Lake Problem: Pathfinding on a slippery grid world.

  Contributions and suggestions are welcome!

