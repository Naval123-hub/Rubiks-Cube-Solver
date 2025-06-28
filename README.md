# 🧩 Rubik's Cube Solver

This project is a **virtual Rubik’s Cube 3x3 simulator and solver**, implemented in C++ using standard data structures and advanced search algorithms. It supports solving scrambled cubes efficiently using optimized algorithms and multiple modeling approaches.

---

## 🚀 Key Features

- 🔄 **Modeled the cube in 3 different ways** using classes and STL containers
- 🔍 Implemented solving algorithms:
  - **Breadth-First Search (BFS)**
  - **Depth-First Search (DFS)**
  - **Iterative Deepening DFS (IDDFS)**
  - **Korf's IDA\*** (Iterative Deepening A\* Search)
- ⏱️ **Performance Highlights**:
  - Solves a cube scrambled 8 times in **under 3 seconds**
  - Solves a cube scrambled 13 times with IDA\* in **under 10 seconds**
- ⚡ Optimized using:
  - **Memoization** to avoid redundant calculations
  - **Pruning** strategies to reduce search space

---

## 🛠️ Technologies Used

- **Language**: C++
- **Tools**: STL (Standard Template Library)
- **Concepts**: Graph search, Heuristics, State-space modeling

---

## 🧑‍💻 Getting Started

### ✅ Prerequisites

- A C++ compiler (e.g., `g++`, `clang`, or Visual Studio)
- Git
- `make` (optional, if a Makefile is provided)

### 🔧 Build & Run

```bash
git clone https://github.com/Naval123-hub/Rubiks-Cube-Solver.git
cd Rubiks-Cube-Solver
g++ -std=c++17 main.cpp -o solver
./solver
