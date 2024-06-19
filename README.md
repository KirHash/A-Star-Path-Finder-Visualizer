# A-Star-Path-Finder-Visualizer

## About
A* (pronounced "A-star") is a graph traversal and pathfinding algorithm, which is used due to its optimality and optimal efficiency. Given a weighted graph, a source node and a goal node, the algorithm finds the shortest path (with respect to the given weights) from source to goal.
It approximate the shortest path in real-life situations, like- in maps, games where there can be many hindrances.

## Key Components:

### Nodes and Graph Representation:
1. Nodes: Points or locations in the grid or graph.
2. Edges: Connections between nodes, often with associated costs or weights.

### Heuristic Function (h):
1. Estimates the cost from any given node to the goal node.
2. Must be admissible (never overestimates the actual cost).

### Cost Functions:
1. Actual Cost (g): The cost to move from the starting node to a given node 𝑛. It is denoted as 𝑔(𝑛).
2. Total Cost (f): The sum of 𝑔(𝑛) and  ℎ(𝑛), denoted as 𝑓(𝑛) = 𝑔(𝑛) + ℎ(𝑛). This represents the estimated total cost of the path through node 𝑛 to the goal.


Although being the best path finding algorithm around, A* Search Algorithm doesn’t produce the shortest path always, as it relies heavily on heuristics

