# AI Eight-Puzzle Solver

A Python-based intelligent agent that solves the classic 8-puzzle problem using a heuristic search algorithm to find the most optimal path to the goal state.

## Features
* **Heuristic Search:** Uses informed search logic to minimize the total path cost.
* **Optimal Pathfinding:** Dynamically calculates the fewest moves required to reach the goal.
* **Performance Metrics:** Tracks explored states and execution paths.

## How It Works
The agent evaluates possible tile movements (Up, Down, Left, Right) by calculating an evaluation function $f(n) = g(n) + h(n)$, where:
* $g(n)$ is the cost to reach the current state.
* $h(n)$ is the estimated heuristic cost to the goal (e.g., Manhattan Distance).

## Setup and Run

1. **Extract the project files:** Unzip `EightPuzzle AI agent.zip` into your workspace.
2. **Open your terminal and navigate to the directory:**
