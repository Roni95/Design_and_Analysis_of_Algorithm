# 🧠 Design and Analysis of Algorithms (C / C++ Implementation)

Welcome to my **Algorithm Course Implementation Repository**!  
This collection contains implementations of classical algorithms developed during my **Design and Analysis of Algorithms (DAA)** coursework.  
The programs cover **Dynamic Programming**, **Greedy Algorithms**, and **Graph Theory**, implemented in **C and C++** to demonstrate optimization, efficiency, and problem-solving strategies.

---

## ⚙️ Topics Covered

### 🧩 Greedy Algorithms
1. **Activity Selection Problem**  
   📄 `activity_selection.cpp`  
   ➤ Selects the maximum number of non-overlapping activities based on start and finish times.

2. **Kruskal’s Algorithm**  
   📄 `kruskals2.cpp`  
   ➤ Finds the **Minimum Spanning Tree (MST)** of a weighted, undirected graph using union–find operations.

3. **Prim’s Algorithm**  
   📄 `prims2.cpp`  
   ➤ Another MST algorithm that grows the spanning tree from a starting vertex by choosing the minimum weight edge.

4. **Vertex Cover Problem (Approximation)**  
   📄 `VertexCoverProblem.cpp`  
   ➤ Approximates a minimal set of vertices covering all edges in a graph.

5. **Travelling Salesman Problem (TSP)**  
   📄 `TraveelingSales.cpp`  
   ➤ Uses greedy or brute-force methods to determine the shortest possible route visiting all cities once.

---

### 🧮 Dynamic Programming Algorithms
1. **Longest Common Subsequence (LCS)**  
   📄 `LCS.cpp`  
   ➤ Finds the length of the longest subsequence common to two strings.

2. **0/1 Knapsack Problem**  
   📄 `knapS.cpp`  
   ➤ Maximizes profit under weight constraints using dynamic programming.

3. **Matrix Chain Multiplication**  
   📄 `matrixchainmultiplication.c`  
   ➤ Determines the optimal order to multiply matrices with minimal computation cost.

4. **N-Queens Problem**  
   📄 `NQueensProblem.cpp`  
   ➤ Solves the N-Queens placement on a chessboard using backtracking and recursion.

---

### 🌐 Graph Algorithms
1. **Maximum Flow of a Network (Ford-Fulkerson Algorithm)**  
   📄 `MaximumFlowOfNetwork.cpp`  
   ➤ Determines the maximum possible flow in a network graph.

2. **Vertex Cover Problem**  
   📄 `VertexCoverProblem.cpp`  
   ➤ Identifies a subset of vertices that touches all edges in a graph — demonstrating combinatorial optimization.

---

### 🔢 Sorting Algorithm
1. **Merge Sort**  
   📄 `margeSort.cpp`  
   ➤ Efficient divide-and-conquer sorting algorithm with O(n log n) complexity.

---

## 🧠 Learning Objectives

Through this repository, learners can:

- Understand and implement **optimization techniques** (Greedy, Divide & Conquer, Dynamic Programming).  
- Analyze **algorithmic complexity** and trade-offs.  
- Develop logical reasoning through **graph-based** and **combinatorial** problem-solving.  
- Strengthen **C/C++ programming proficiency** for academic and competitive programming use.

---

## 🧰 Tools and Technologies

- **Languages:** C, C++  
- **Concepts Covered:**  
  - Dynamic Programming  
  - Greedy Algorithms  
  - Graph Theory  
  - Recursion and Backtracking  
  - Optimization Techniques  
- **IDE / Compiler:** GCC, Code::Blocks, Dev-C++, Visual Studio Code

---

## 🚀 How to Run

1. Clone or download the repository.  
2. Open a terminal and compile any file using:
   ```bash
   g++ filename.cpp -o output
   ./output
