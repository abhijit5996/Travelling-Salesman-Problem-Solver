
# OptimalWay - Traveling Salesman Problem Solver

![OptiRouteX Screenshot](![Ai project](https://github.com/user-attachments/assets/5e494abe-16d2-4f27-ba25-3ffddca049aa)
)

OptiRouteX is an interactive web application that visualizes various algorithms for solving the Traveling Salesman Problem (TSP). With a cyberpunk-inspired UI, it allows users to create graphs, connect nodes with weighted edges, and find optimal routes using different computational approaches.

## Features

- **Interactive Graph Editor**:
  - Add nodes by clicking on the canvas
  - Connect nodes with weighted/directed edges
  - Delete nodes or edges
  - Select start and end points

- **Multiple TSP Algorithms**:
  - Brute Force (exact solution for small graphs)
  - Branch & Bound (optimized exact solution)
  - Nearest Neighbor (heuristic)
  - Greedy Approach (iterative improvement)
  - Genetic Algorithm (evolutionary approach)

- **Visualization Tools**:
  - Animated solution paths
  - Highlighted optimal routes
  - Edge weight labels
  - Node identification

- **Customizable Parameters**:
  - Algorithm-specific settings
  - Weighted/unweighted edges
  - Directed/undirected graphs

## How to Use

1. **Create Your Graph**:
   - Select "Add Nodes" mode to place cities on the canvas
   - Switch to "Connect Nodes" to create edges between cities
   - Use "Select Start/End" to define your route endpoints

2. **Configure Algorithm**:
   - Choose from 5 different solving algorithms
   - Adjust algorithm-specific parameters as needed

3. **Solve and Visualize**:
   - Click "Solve TSP" to find the optimal route
   - View the solution path and statistics
   - Watch the animated path visualization

4. **Reset**:
   - Use the "Reset" button to clear the canvas and start over

## Technologies Used

- HTML5 Canvas for graph visualization
- Vanilla JavaScript for algorithm implementation
- CSS3 for cyberpunk-themed styling
- Google Fonts (Orbitron and Rajdhani) for typography

## Algorithms Implemented

1. **Brute Force**:
   - Tests all possible permutations
   - Guaranteed optimal solution
   - Only practical for small graphs (n ≤ 10)

2. **Branch & Bound**:
   - Optimized exact solution
   - Uses bounding heuristics to prune search space
   - Configurable time limit and branching factor

3. **Nearest Neighbor**:
   - Greedy heuristic approach
   - Always chooses closest unvisited city
   - Fast but not always optimal

4. **Greedy Approach**:
   - Iterative improvement
   - Runs multiple random starts
   - Configurable iteration count

5. **Genetic Algorithm**:
   - Evolutionary approach
   - Population-based optimization
   - Configurable population size, generations, and mutation rate

## Installation

No installation required! Simply open the `index.html` file in any modern web browser.

## Future Enhancements

- Additional algorithms (e.g., Simulated Annealing, Ant Colony Optimization)
- Save/Load graph functionality
- Performance optimizations for larger graphs
- Export solution as image or data file

## License

This project is open-source and available under the MIT License.

---

**Note**: For optimal performance with larger graphs, consider using more efficient algorithms or implementing Web Workers for background computation. The brute force method is intentionally limited to prevent browser freezes with complex graphs.
