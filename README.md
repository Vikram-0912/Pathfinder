# PathFinding-Visualizer

A web-based pathfinding visualizer built with React that demonstrates various pathfinding algorithms in action. This tool allows users to visualize how different algorithms explore and find paths in a grid-based environment.

Access the website here: https://algorithmsvisualizer.github.io/PathFinding-Visualizer/

## Features

- Interactive grid where you can set start and end points
- Visualize pathfinding algorithms in real-time
- Add walls to create obstacles
- Generate random mazes
- Adjust algorithm parameters (e.g., movement directions)
- Responsive design

## Supported Algorithms

### A* Search
An informed search algorithm that uses heuristics to find the shortest path. It combines the advantages of Dijkstra's algorithm and greedy best-first search. A* is optimal and complete.

### Breadth-First Search (BFS)
An unweighted search algorithm that explores nodes level by level. Guarantees the shortest path in unweighted graphs. Uses a queue data structure.

### Depth-First Search (DFS)
An unweighted search algorithm that explores as far as possible along each branch before backtracking. Does not guarantee the shortest path. Uses a stack data structure.

### Dijkstra's Algorithm
A weighted search algorithm that finds the shortest path between nodes in a graph with non-negative edge weights. Uses a priority queue (binary heap) to always expand the node with the smallest distance.

## Mazes

The visualizer includes several maze generation algorithms:

- **Basic Random**: Randomly places walls on the grid
- **Basic Weight**: Creates weighted nodes for more complex pathfinding
- **Recursive Division**: Generates mazes using recursive division
- **Simple Stair**: Creates a simple staircase pattern

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Vikram-0912/Pathfinder.git
   cd Pathfinder
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Technologies Used

- React
- JavaScript
- HTML5
- CSS3

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
