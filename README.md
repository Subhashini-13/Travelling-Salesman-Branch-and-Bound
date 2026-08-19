# 🗺️ Travelling Salesman Problem using Branch and Bound

An interactive and modern web-based implementation of the **Travelling Salesman Problem (TSP)** using the **Branch and Bound algorithm**.

The project demonstrates how Branch and Bound can be used to find an optimal travelling route while minimizing the total travelling cost.

## 🌐 Live Implementation

👉 **[View the Live Website](https://subhashini-13.github.io/Travelling-Salesman-Branch-and-Bound/)**

---

## 📌 About the Project

The **Travelling Salesman Problem (TSP)** is a classic optimization problem in Computer Science.

Given a set of cities and the distances between them, the objective is to find the shortest possible route that:

- 🏙️ Visits every city exactly once
- 🔄 Returns to the starting city
- 💰 Minimizes the total travelling cost

This project uses the **Branch and Bound technique** to explore possible routes and eliminate unnecessary branches.

---

## 🌳 Branch and Bound Approach

The algorithm works using three main ideas:

### 1. 🌱 Branch

The problem is divided into smaller possible paths by selecting the next city.

### 2. 📏 Bound

A cost estimate or bound is calculated for each partial route.

### 3. ✂️ Prune

If a partial route cannot produce a better solution than the current best route, that branch is discarded.

This helps reduce unnecessary searching.

---

## 🖥️ Features

- 🎨 Modern and colorful user interface
- 🟠 Orange and 🟢 Green theme
- 🗺️ Interactive TSP visualizer
- 🔢 Select the number of cities
- 🚀 Generate an optimal route
- 🏆 Display the optimal path
- 💰 Display the minimum travelling cost
- 📊 Complexity analysis
- 🌳 Explanation of Branch and Bound
- 📚 Key algorithm concepts
- 📱 Responsive design for different screen sizes

---

## 🔄 How the Algorithm Works

The Branch and Bound algorithm:

1. Starts from the first city.
2. Generates possible next cities.
3. Calculates the current path cost.
4. Explores unvisited cities.
5. Compares the current cost with the best known solution.
6. Prunes branches that cannot produce a better solution.
7. Visits all cities.
8. Returns to the starting city.
9. Updates the minimum cost and optimal route.

---

## 🧠 Key Concepts

### 🗺️ Hamiltonian Cycle

A route that visits every city exactly once and returns to the starting city.

### 🌳 State Space Tree

Represents all possible routes that can be explored.

### ✂️ Pruning

Eliminates branches that cannot provide a better solution.

### 🏆 Optimization

Finds the minimum-cost route among the possible routes.

---

## ⏱️ Complexity

### Time Complexity

```text
O(N!)
