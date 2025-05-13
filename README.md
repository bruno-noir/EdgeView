# EdgeView - Graph Traversing Visualization

Graph Traversing Visualization is an interactive tool for creating, manipulating, and traversing graphs using **Vanilla JavaScript** and the **Canvas API**. It supports various edge types and visualizes standard graph traversal algorithms such as depth-first and breadth-first search.

---

## Demo

Run the live version in your browser:  
[**Open Demo**](#) *(insert link here)*

---

## Example Screenshot

Here is a sample visualization of a graph with traversal paths:
![out](https://github.com/user-attachments/assets/cedb2470-1613-4450-b60a-33461739a387)



---

## Features
![edgeview](https://github.com/user-attachments/assets/235601e9-b0a7-4b39-848e-5d41aa55ce52)


- Interactive graph building with drag-and-drop support
- Directed, undirected, and parallel edge support
- Real-time updates of:
  - Adjacency matrix
  - Incidence matrix
  - Adjacency list
- Vertex deletion (with all connected edges)
- Visualization of:
  - Depth-First Search (DFS)
  - Breadth-First Search (BFS)

---

## Controls

| Task                                     | Action                                           |
|------------------------------------------|--------------------------------------------------|
| Create vertex                            | Left-click on an empty canvas space              |
| Move vertex                              | Hold left mouse button and drag                  |
| Connect two vertices                     | Right-click on both vertices (start and end)     |
| Delete a vertex                          | Ctrl + Right-click on the vertex                 |
| Select a vertex as start for DFS/BFS     | Ctrl + Left-click on the vertex                  |

---

## Getting Started

### Clone and Run

```bash
git clone https://github.com/bruno-noir/EdgeView.git
cd EdgeView
```
```bash
npm install
npm run test
```
### Test Result Screenshot

![test](https://github.com/user-attachments/assets/8b120496-95ba-480f-879b-aa7a1bc21ff5)

