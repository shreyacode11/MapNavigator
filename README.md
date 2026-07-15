# 🗺️ Map Navigator

<p align="center">
  <img src="assets/logo.png" alt="Map Navigator Logo" width="180"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-17+-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Data%20Structures-Graphs-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Algorithm-Dijkstra-success?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge">
</p>

## 📖 Overview

Map Navigator is a Java-based application that finds the shortest path between locations using **Dijkstra's Algorithm**. It models cities and roads as a weighted graph and calculates the optimal route based on the minimum travel distance.

This project demonstrates practical applications of **Graph Theory**, **Data Structures**, and **Object-Oriented Programming**.

---

# ✨ Features

- 🗺️ Shortest Path Calculation
- 📍 Weighted Graph Representation
- ⚡ Dijkstra's Algorithm Implementation
- 📏 Distance Calculation
- 📊 Efficient Route Selection
- 💻 Console-Based Interface
- 🧩 Modular Java Code
- 📚 Object-Oriented Design

---

# 🏗️ System Workflow

```
User Input
     │
     ▼
Source & Destination
     │
     ▼
Build Weighted Graph
     │
     ▼
Run Dijkstra Algorithm
     │
     ▼
Find Shortest Path
     │
     ▼
Display Route & Distance
```

---

# 🛠️ Tech Stack

- Java
- Object-Oriented Programming (OOP)
- Graph Data Structure
- Dijkstra's Algorithm

---

# 📂 Project Structure

```
MapNavigator/
│
├── src/
│   ├── Graph.java
│   ├── Dijkstra.java
│   ├── Node.java
│   ├── Edge.java
│   └── Main.java
│
├── assets/
│   ├── output.png
│   ├── graph.png
│   └── logo.png
│
├── README.md
└── LICENSE
```

*(Adjust filenames if your project structure differs.)*

---

# ⚙️ Algorithm

1. Create a weighted graph.
2. Select source node.
3. Initialize all distances as infinity.
4. Set source distance to 0.
5. Visit the nearest unvisited node.
6. Relax adjacent edges.
7. Repeat until destination is reached.
8. Display the shortest path and total distance.

---

# 📸 Screenshots

## Console Output

![](assets/output.png)

---

## Graph Representation

![](assets/graph.png)

---

# 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/shreyacode11/map-navigator.git
```

### Compile

```bash
javac *.java
```

### Run

```bash
java Main
```

---

# 📈 Time Complexity

| Operation | Complexity |
|-----------|-----------:|
| Dijkstra Algorithm | O((V + E) log V) |
| Graph Construction | O(E) |

---

# 🎯 Learning Outcomes

- Graph Data Structures
- Dijkstra's Algorithm
- Java Collections Framework
- Object-Oriented Programming
- Algorithm Optimization

---

# 🚀 Future Improvements

- 🖥️ Java Swing GUI
- 🌍 Interactive Map Visualization
- 📍 GPS Integration
- 🚦 Traffic-Aware Routing
- 🛣️ Multiple Shortest Path Algorithms (A*, Bellman-Ford)
- ☁️ Database Integration
- 🌐 Web-Based Version

---

# 👩‍💻 Author

**Shreya Saboji**

Information Science Engineering Student

- Java Developer
- Full Stack Developer
- IoT Enthusiast

---

# 📄 License

This project is licensed under the MIT License.

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
