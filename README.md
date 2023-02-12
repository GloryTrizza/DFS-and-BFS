# DFS-and-BFS

## Overview
This program is a implementation of the Agent class which is used to perform depth first search (DFS) and breadth first search (BFS) on a graph represented as a dictionary. The graph, start node, and goal node are defined in the Environment class.

## Environment Class
The Environment class contains the graph representation, the start node, and the goal node. The graph is represented as a dictionary where each key is a node and the values are a set of connected nodes.

## Agent Class
The Agent class contains two methods for searching the graph: DFS and BFS.

The DFS method implements the depth first search algorithm. It uses a stack to store the vertices and paths and the algorithm works by removing elements from the stack and visiting unvisited neighbors. If a path to the goal is found, it is added to the list of paths.

The BFS method implements the breadth first search algorithm. It uses a queue to store the vertices and paths and the algorithm works by removing elements from the front of the queue and visiting unvisited neighbors. If a path to the goal is found, it is added to the list of paths and the function returns.

The __init__ method of the Agent class takes the Environment object as an input and calls the DFS and BFS methods, printing the paths found by each method.

## Usage
To use this program, create an instance of the Environment class and pass it to the Agent class. The paths found by DFS and BFS will be printed.
