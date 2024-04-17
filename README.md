# Shortest Path Algorithms
This project implements three shortest path algorithms in C++: Prim's algorithm, Kruskal's algorithm, and Dijkstra's algorithm. <br />

## Algorithms Implemented
Prim's Algorithm: This algorithm finds the minimum spanning tree (MST) for a weighted undirected graph. It starts with an empty spanning tree and adds the closest vertex to the tree at each step, ensuring no cycles are formed. <br />

Kruskal's Algorithm: Similar to Prim's algorithm, Kruskal's algorithm also finds the minimum spanning tree of a graph. However, it does so by adding edges in increasing order of weight and ensuring that no cycles are formed. <br />

Dijkstra's Algorithm: This algorithm finds the shortest path from a single source vertex to all other vertices in a weighted graph. It maintains a set of vertices whose shortest distance from the source is known and iteratively finds the shortest path to the remaining vertices. <br />

## Implementation
The algorithms are implemented in C++ using object-oriented programming concepts. <br />
The graph is represented using adjacency lists for efficient storage and traversal. <br />
The algorithms are implemented as member functions of a Graph class, making it easy to use and test. <br />
## Usage
Clone this repository. <br />
Compile the source code using a C++ compiler (e.g., g++). <br />
Run the executable file and follow the on-screen instructions to choose the algorithm and input graph. <br />

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
