# CAMPUS-25-NAVIGATION

## Campus Navigation Using Dijkstra's Algorithm

### About the Project
This project finds the shortest path between two locations on a campus using Dijkstra's Shortest Path Algorithm. The campus is represented as a weighted graph covering four floors.

### How It Works
- Rooms, staircases, and other locations are represented as nodes.
- Connections between locations are represented as weighted edges, based on the number of steps.
- An adjacency list is used to store the graph.
- Dijkstra's algorithm calculates the minimum steps between the source and destination.
- The program displays the minimum steps and the shortest path.

### Technologies Used
- **Language:** C++
- **Algorithm:** Dijkstra's Shortest Path Algorithm
- **Data Structure:** Weighted Graph using an Adjacency List

### How to Run
1. Clone or download this repository.
2. Open the project folder in a terminal.
3. Compile the C++ program:

   ```bash
   g++ -std=c++17 code.cpp -o campus_navigation
   ```

4. Run the program:

   ```bash
   ./campus_navigation
   ```

5. Enter the source and destination locations when prompted.

### Project Objective
To apply graph algorithms to a real-world campus navigation problem and find the minimum-step route between locations across multiple floors.
