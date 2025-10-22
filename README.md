# <div align="center">
# <img src="https://cdn.freebiesupply.com/logos/large/2x/sharif-logo-png-transparent.png" width=150 height=150>
# <br>
# <font color=0F5298>
# Artificial Intelligence - Practical Assignment
# </font>
# </div>

### 📌 **AI Problem Solving: CSP, Cryptarithmetic & Adversarial Search**

This repository contains the practical assignment for the Artificial Intelligence course, focusing on three fundamental areas of AI problem-solving.
---

## 🚀 Project Overview

This project is a hands-on implementation of core AI algorithms. It is divided into three main parts, each with a unique narrative and technical challenge:

1.  **🏰 The Kingdom Conflict of Eldoria:** A Constraint Satisfaction Problem (CSP) modeled as a **Graph Coloring** problem.
2.  **🔢 Unlocking the Treasure:** A classic **Cryptarithmetic Puzzle** solved using CSP techniques.
3.  **🎮 The Hidden Challenge:** An **Adversarial Search** problem where an AI agent is built to play the game of **Othello**.

---

## 🛠️ Algorithms & Techniques Implemented

This project covers the implementation and application of the following algorithms and heuristics:

* **Constraint Satisfaction Problems (CSP)**
    * Backtracking Search
    * AC-3 Algorithm (for constraint propagation)
    * Minimum Remaining Values (MRV) Heuristic
    * Least Constraining Value (LCV) Heuristic
* **Adversarial Search**
    * Minimax Algorithm
    * Alpha-Beta Pruning
    * Expectimax

---

## 📂 Project Structure

### Part 1: 🏰 The Kingdom Conflict (Graph Coloring CSP)

* **Problem:** The land of Eldoria is composed of rival kingdoms. The task is to assign a "ruling faction" (color) to each kingdom (node) such that no two adjacent rival kingdoms (connected by an edge) share the same faction.
* **Goal:** Find a valid assignment of factions using the minimum number of colors, implementing Backtracking search optimized with **AC-3**, **MRV**, and **LCV** heuristics.

### Part 2: 🔢 Unlocking the Treasure (Cryptarithmetic CSP)

* **Problem:** A treasure chest is locked by a cryptarithmetic puzzle (e.g., `GOLD + COIN = CHEST`). Each letter must be assigned a unique digit (0-9) so the equation holds true.
* **Goal:** Implement a Backtracking solver to find the unique digit-to-letter mapping that solves the puzzle, enforcing uniqueness and no-leading-zero constraints.

### Part 3: 🎮 The Hidden Challenge (Othello AI)

* **Problem:** An ancient board game (Othello) is discovered. The task is to build an intelligent AI agent that can play and win the game.
* **Goal:** Implement AI agents using **Minimax**, **Alpha-Beta Pruning**, and **Expectimax** to find the optimal move at each turn.

---

## 🎯 Learning Objectives

By completing this assignment, the following objectives are achieved:

✅ Understanding and formulating problems as **Constraint Satisfaction Problems (CSPs)**.
✅ Implementing **Backtracking Search** for solving CSPs.
✅ Applying heuristics like **MRV** and **LCV** to optimize search.
✅ Using **AC-3** for constraint propagation.
✅ Solving complex **Cryptarithmetic Puzzles**.
✅ Implementing **Adversarial Search Algorithms** (Minimax, Alpha-Beta, Expectimax) for a 2-player game.
