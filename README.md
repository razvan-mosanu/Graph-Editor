# Graph Editor Pro

**Graph Editor Pro** is a comprehensive web-based application for creating, visualizing, and manipulating graph structures. Designed as an educational tool, it allows users to experiment with graph theory concepts directly in the browser.

> **Project Type:** Professional Certification in Informatics (Atestat Profesional)  
> **Student:** Moșanu Răzvan Alexandru  
> **Supervisor:** Prof. Dan Pracsiu  
> **Institution:** Liceul Teoretic „Emil Racoviță” Vaslui  
> **Year:** 2025

## 🌟 Key Features

This application has been upgraded with professional features to ensure a smooth workflow:

### 🛠️ Graph Manipulation
* **Interactive Canvas:** Click to add nodes, click-and-drag to move them.
* **Smart Connections:** Click a source node (highlighted orange) then a target node to create an edge.
* **Directed/Undirected:** Toggle between directed edges (arrows) and undirected edges (lines) instantly.
* **Custom Indexing:** Choose to start node indexing from `0` or `1`.
* **Responsive Design:** The drawing canvas automatically resizes to fit your screen or window.

### 🚀 Advanced Tools
* **Undo / Redo System:** A robust history system that remembers every action (node additions, movements, edge creation). You can safely step back and forth through your changes.
* **Adjacency Matrix:** Automatically generates a real-time `0/1` matrix table below the canvas representing the graph's connections (optimized for up to 20 nodes).
* **Save & Load Projects:**
    * **Export JSON:** Save your graph structure (nodes, edges, positions) to a `.json` file to continue working later.
    * **Import JSON:** Reload a previously saved project instantly.
    * **Save PNG:** Export the current visual representation of the graph as an image.

## 💻 Tech Stack
* **HTML5 Canvas:** For high-performance rendering of nodes and edges.
* **Vanilla JavaScript (ES6):** Core logic, state management, and DOM manipulation (no external libraries required).
* **CSS3:** Modern, responsive styling using Flexbox.

## 📖 Usage Guide

1.  **Adding Nodes:** Click anywhere on the white canvas or use the "Add Node" button for a grid layout.
2.  **Creating Edges:**
    * Click the **Source Node** (it turns Orange).
    * Click the **Target Node**.
    * *Note: To cancel a selection, click the source node again.*
3.  **Moving Nodes:** Simply drag and drop nodes to rearrange the graph. The edges will follow automatically.
4.  **Deleting Items:**
    * Click the **Delete Mode** button (it turns Red).
    * Click on any Node or Edge to remove it.
    * *Tip: Click "Delete Mode" again to return to editing.*
5.  **History:** Use the **Undo** and **Redo** buttons to correct mistakes.

## 🚀 How to Run (No Installation)

You can access the live version of this project directly via GitHub Pages:

[**🔗 Click here to open Graph Editor**](https://razvan-mosanu.github.io/Graph-Editor/)

### Running Locally
1.  Clone this repository.
2.  Open `index.html` in any modern web browser (Chrome, Firefox, Edge).

---
*This project demonstrates the practical application of web technologies in modeling complex data structures.*
