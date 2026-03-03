# Dynamic Pathfinding Agent

This project is a comprehensive implementation of two fundamental Artificial Intelligence search algorithms:

- **A\* Search**
- **Greedy Best-First Search (GBFS)**

The system is built using **Python** and **Pygame** to visually demonstrate pathfinding behavior in a 2D grid environment.

---

## 🚀 Features

- Interactive 2D grid (up to 30×30)
- Click-to-toggle wall creation
- Random maze generator
- Two heuristics:
  - Manhattan Distance
  - Euclidean Distance
- Dynamic obstacle mode with live replanning
- Real-time metrics display:
  - Nodes Visited
  - Path Cost
  - Execution Time (ms)
- Visual color legend for:
  - Optimal Path
  - Visited Nodes
  - Frontier
  - Walls
  - Goal

---

## 🧠 Algorithms Implemented

### 🔹 A\* Search
- Uses `f(n) = g(n) + h(n)`
- Complete and Optimal
- Guarantees shortest path with admissible heuristic

### 🔹 Greedy Best-First Search (GBFS)
- Uses only heuristic `h(n)`
- Faster in open environments
- Not guaranteed optimal

---

## 📊 Experimental Analysis

- A\* consistently finds optimal paths
- GBFS performs faster in clear grids
- Manhattan heuristic outperforms Euclidean in 4-directional grid
- A\* handles dynamic replanning more reliably

---

## 🛠️ Technologies Used

- Python
- Pygame
- Priority Queue (Heap)
- Object-Oriented Design

---

## 🎓 Course Information

- **Course:** Artificial Intelligence  
- **Assignment:** Search Algorithms  
- **Program:** BSCS
