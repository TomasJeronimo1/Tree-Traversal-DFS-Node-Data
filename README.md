# Tree-Traversal-DFS-Node-Data

# Project Overview
This project addresses a limitation in the original data source, where hierarchical relationships were not fully represented in a structured format. The CSV file provided only partial information, making it difficult to analyze full node hierarchies.

The goal was to transform the dataset into a complete hierarchical tree, ensuring that each row represents an entire path from the root node to a leaf node, regardless of the hierarchy depth.

# Solution
To achieve this, I implemented a Depth-First Search (DFS) algorithm with backtracking. This recursive method allowed me to efficiently traverse and restructure the data, ensuring all possible hierarchical paths were extracted accurately.

With this transformation, hierarchical data becomes significantly easier to manage, analyze, and visualize.
For personal curiosity and for future reference, the Time Complexity here is O(N). Given N number of nodes, each node is visited once.
