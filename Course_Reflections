---
title: Algorithm Concepts
---

## 1. Types of Problems in Nature

**Iteration**: Repetition of a process in a loop-like manner.  
*Example*: Seasonal changes (spring, summer, autumn, winter) follow a cyclic iterative pattern.

**Recursion**: A process calling itself, often with a smaller problem size.  
*Example*: Tree branching follows a recursive pattern.

**Backtracking**: Exploring potential paths to achieve a goal, backing up when necessary.

## 2. Space and Time Efficiency

**Time Efficiency**: Measures how long an algorithm takes as input size grows. Faster algorithms handle larger inputs in less time.

**Space Efficiency**: Measures memory usage of an algorithm. Less memory usage means faster access and better performance.

### Classes of Problems

- **Constant**: O(1)
- **Logarithmic**: O(log(n))
- **Linear**: O(n)
- **Quadratic**: O(n²)
- **Cubic**: O(n³)
- **Exponential**: O(2ⁿ)
- **Factorial**: O(n!)

### Orders of Growth

- **Best Case**: The fastest scenario (e.g., finding the first item in a search).
- **Average Case**: A realistic view of performance.
- **Worst Case**: The slowest or most resource-intensive scenario.

## 3. Takeaway from Different Design Principles (Chapter 2)

- **Bubble Sort**: O(n²) - Repeatedly compare and swap adjacent items.
- **Selection Sort**: O(n²) - Find and move the smallest item repeatedly.
- **Merge Sort**: O(n log n) - Divide, sort, and merge.
- **Quick Sort**: O(n log n) - Partition around a pivot and sort recursively.
- **Insertion Sort**: O(n²) (worst case) - Insert elements one at a time into the correct position.
- **Heap Sort**: O(n log n) - Uses a binary heap structure.
- **Boyer-Moore**: Efficient string-searching algorithm.
- **Kruskal's Algorithm**: Finds the minimum spanning tree.
- **Floyd-Warshall Algorithm**: O(n³) - Finds shortest paths between all pairs of nodes.
- **Prim's Algorithm**: Builds a minimum spanning tree by selecting smallest edges.

## 4. Hierarchical Data and Tree Data Structures

Hierarchical data is organized like a tree with parent-child relationships.

- **Tree**: A hierarchical structure with nodes and edges.
- **Binary Search Tree (BST)**: Created by taking the first incoming element as the root node, with all items lesser than the root moved to the left and greater than or equal to the right side of the tree. O(log n) (average), O(n) (worst case) - Efficient but slows if unbalanced.
- **AVL Tree**: O(log n) - Self-balancing BST. In an AVL tree, the heights of the two child sub-trees of any node differ by 0 or 1.
- **2-3 Tree**: O(log n) - A 2-3 Tree has either a 2-node (2 children with 1 data key present) or a 3-node (3 children with 2 data keys present).
- **Red-Black Tree**: O(log n) - Balances using color rules.
- **Heap**: Efficient for priority tasks (e.g., min/max operations).
- **Trie**: Fast for prefix searches and autocomplete.

## 5. Array Query Algorithms

Essential for efficiently processing and retrieving information from arrays.

**Need**: Faster operations for large datasets.  
**Principle**: Preprocess data to enable fast queries and updates.  
**Applications**: Range sums, min/max calculations, and data updates.

## 6. Differentiating Trees and Graphs

**Trees**: Hierarchical, acyclic, single root, one path between nodes.  
**Graphs**: General structures, cyclic or acyclic, multiple paths.

### Traversals

**Tree Traversals**

- Inorder: (Left, Root, Right)
- Preorder: (Root, Left, Right)
- Postorder: (Left, Right, Root)

**Graph Traversals**

- Depth-First Search (DFS)
- Breadth-First Search (BFS)

## 7. Determining the Most Efficient Approach to Solve a Complex Problem

- **Understand the Problem**: Clearly define the inputs, outputs, constraints, and objectives.
- **Analyze Complexity**: Consider the problem size and required performance (time and space complexities).
- **Break Down the Problem**: Divide it into manageable parts and identify any subproblems or overlapping substructures.
- **Choose the Right Algorithmic Paradigm**: Use Divide and Conquer, Dynamic Programming, Greedy, or Backtracking based on the problem nature.
- **Test and Optimize**: Implement a solution, analyze its performance, and refine it if needed.

## 8. Balancing Multiple Conflicting Constraints in Design

In situations involving conflicting constraints (e.g., optimizing performance while minimizing memory usage):

- **Identify and Prioritize Constraints**: Determine which constraints are more critical.
- **Use Trade-Off Analysis**: Evaluate how relaxing one constraint affects others.
- **Iterative Refinement**: Implement an initial solution and iteratively improve it based on feedback or testing.

**Example**: Designing a mobile app feature where low memory usage was critical but performance couldn't be compromised. I chose algorithms optimized for space and used caching for frequently accessed data to balance the constraints.

## 9. Sorting and Searching Algorithms

### Sorting Algorithms

- **Bubble Sort**: Compare and swap adjacent elements.
- **Merge Sort**: Divide, sort, and merge.
- **Quick Sort**: Efficient for large datasets, uses partitioning.
- **Insertion Sort**: Good for small or nearly sorted data.

### Searching Algorithms

- **Linear Search**: Check each element in sequence.
- **Binary Search**: Divide and conquer in sorted data.
- **DFS**: Explore deeply before backtracking.

## 10. Importance of Graph Algorithms

### Spanning Trees

Minimize connectivity costs in networks.

### Shortest Paths

Optimize routes for navigation and communication.

### Applications

GPS systems, network design, and data packet routing.

## 11. Studied Algorithm Design Techniques

### Backtracking

Backtracking is like trying to solve a puzzle by making a series of guesses, and if a guess turns out to be wrong, you backtrack and try a different guess. Examples include the N-Queens Problem.

### Kruskal's Algorithm

Kruskal's Algorithm adds edges in increasing order of weight, avoiding cycles, until all vertices are connected.

### Dijkstra's Algorithm

Dijkstra's Algorithm finds the shortest path from a source vertex to all other vertices in a graph with non-negative weights.
