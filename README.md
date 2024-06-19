# A-Star-Path-Finder-Visualizer

## About
A* (pronounced "A-star") is a graph traversal and pathfinding algorithm, which is used due to its optimality and optimal efficiency. Given a weighted graph, a source node and a goal node, the algorithm finds the shortest path (with respect to the given weights) from source to goal.
It approximate the shortest path in real-life situations, like- in maps, games where there can be many hindrances.

## Key Components:

### Nodes and Graph Representation:
Nodes: Points or locations in the grid or graph.
Edges: Connections between nodes, often with associated costs or weights.

### Heuristic Function (h):
Estimates the cost from any given node to the goal node.
Must be admissible (never overestimates the actual cost).

### Cost Functions:

g(n): Cost from the start node to node 
𝑛
n.

Although being the best path finding algorithm around, A* Search Algorithm doesn’t produce the shortest path always, as it relies heavily on heuristics

