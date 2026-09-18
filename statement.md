# Graph Algorithm Visualizer — Project Statement

## 1. Problem Statement

Graph algorithms are an important part of computer science, Artificial Intelligence, and Machine Learning. However, for beginners, understanding how an algorithm actually moves through a graph can be difficult when it is explained only through code or theory.

The **Graph Algorithm Visualizer** is developed to make this learning process easier. The project focuses on two fundamental graph traversal algorithms: **Breadth-First Search (BFS)** and **Depth-First Search (DFS)**. Instead of showing only the final traversal order, the program visually shows the traversal step by step, making it easier to follow which node is currently being explored and which nodes have already been visited.

The project also allows users to work with a pre-built sample graph or create their own graph by entering connections between nodes. This gives students an opportunity to experiment with different graph structures and understand how the choice of traversal algorithm affects the order in which nodes are explored.

Overall, the problem addressed by this project is the difficulty of understanding graph traversal algorithms through text and code alone. The visual approach provides a more practical and beginner-friendly way to learn these concepts.

## 2. Scope of the Project

The scope of this project is focused on the visualization and basic learning of graph traversal algorithms.

The project includes:

- Visualization of **Breadth-First Search (BFS)**.
- Visualization of **Depth-First Search (DFS)**.
- Option to run both algorithms sequentially for comparison.
- A ready-made sample graph for quick demonstration.
- Creation of custom graphs using simple edge input.
- Selection of a starting node before traversal.
- Step-by-step visual feedback during traversal.
- Terminal output showing graph connections and traversal order.
- Color-coded nodes to make the current and visited states easy to understand.
- Basic input validation and helpful error messages.

The project is mainly intended as an **educational and demonstration tool**. It does not attempt to implement every graph algorithm or provide a complete graph-analysis platform. The current version concentrates on making BFS and DFS concepts clear through simple interaction and visualization.

## 3. Target Users

The project is designed mainly for people who are learning or revising graph algorithms.

### Primary Users

- **Computer Science students** learning Data Structures and Algorithms.
- **AI/ML students** studying search and graph-based concepts.
- **Beginners in Python** who want to understand algorithms through a working example.
- **Students preparing for practicals or examinations** involving BFS and DFS.

### Secondary Users

- Teachers or instructors who want a simple classroom demonstration tool.
- Learners who want to experiment with their own graph structures.
- Anyone interested in seeing how graph traversal works visually.

The interface is intentionally kept simple so that users can focus on understanding the algorithm rather than learning a complicated software interface.

## 4. High-Level Features

### 4.1 Sample Graph

The project provides a pre-built graph that can be loaded for an immediate demonstration. The sample graph contains eight nodes and helps users understand the basic traversal process without having to create a graph first.

### 4.2 Custom Graph Creation

Users can create their own graph by entering edges in a simple format such as `node1 node2`. This makes it possible to experiment with different connections and graph structures.

### 4.3 BFS Visualization

The BFS option demonstrates **Breadth-First Search**, which explores the graph level by level. The program uses a queue and visually updates the graph as nodes are visited.

### 4.4 DFS Visualization

The DFS option demonstrates **Depth-First Search**, which explores one branch as deeply as possible before backtracking. The implementation uses recursion to perform the traversal.

### 4.5 Step-by-Step Visual Feedback

The graph is updated during traversal so users can follow the algorithm's progress instead of seeing only the final result.

### 4.6 Color-Coded Nodes

Different colors are used to represent the state of nodes:

- 🔴 **Red** — current node being explored.
- 🟢 **Green** — node that has already been visited.
- 🔵 **Blue** — node that has not been visited yet.

This makes the traversal easier to follow visually.

### 4.7 Traversal Order

Along with the graphical visualization, the program displays the traversal order in the terminal. This allows users to connect the visual movement of the algorithm with its actual output.

### 4.8 User-Friendly Interaction

The program provides clear menu options, basic input validation, and messages for incorrect input or unavailable nodes. The aim is to keep the experience straightforward for beginners.

---

## Project Goal

The main goal of the **Graph Algorithm Visualizer** is simple: **to turn an abstract graph traversal concept into something students can see and follow step by step.**

By combining Python, NetworkX, and Matplotlib, the project connects algorithm theory with practical visualization and gives learners a hands-on way to explore BFS and DFS.
