# N-Queens Visualizer using Backtracking Algorithm

## Overview

This project is an interactive web-based visualization tool designed to demonstrate how the **Backtracking Algorithm** solves the classic **N-Queens Problem** in real time.

The application visually places queens on an N×N chessboard while ensuring no two queens attack each other, helping users understand recursion, backtracking, and algorithmic decision-making step by step.

### Live Demo:

https://nqueensvisualizer-backtracking.netlify.app/

---

## Problem Statement

The N-Queens Puzzle requires placing N queens on an N×N chessboard such that:

* No two queens share the same row
* No two queens share the same column
* No two queens share the same diagonal

This project aims to:

* Visualize the recursive backtracking process
* Improve understanding of DSA concepts
* Provide an interactive educational tool
* Demonstrate real-time problem-solving

---

## Technologies Used

* HTML
* CSS
* JavaScript
* Backtracking Algorithm
* Recursion

---

## Features

### Core Functionalities:

* Dynamic chessboard generation
* Real-time queen placement visualization
* Conflict detection system
* Step-by-step backtracking animation
* Adjustable board sizes
* Interactive controls for visualization
* Algorithm execution logs

---

## Project Workflow

### 1. User Input

* Select board size (N)

---

### 2. Board Initialization

* Dynamic generation of N×N chessboard

---

### 3. Recursive Backtracking

* Place queens row by row
* Check:

  * Column safety
  * Left diagonal safety
  * Right diagonal safety
* Backtrack when conflicts occur

---

### 4. Visualization

* Display queen placements
* Show failed attempts
* Demonstrate recursive corrections

---

## Algorithm Used

### Backtracking Logic:

```txt id="w1n8ms"
Place queen row-wise
↓
Check validity
↓
If valid → continue
↓
If invalid → backtrack
↓
Repeat until solution found
```

---

## Learning Outcomes

This project strengthens:

* Recursion
* Backtracking
* Problem-solving
* DSA fundamentals
* Visualization design
* Frontend integration

---

## Key Concepts Demonstrated

* Recursive search
* Constraint satisfaction
* State-space exploration
* Conflict pruning
* Algorithm optimization

---

