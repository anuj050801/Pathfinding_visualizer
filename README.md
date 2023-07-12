# Pathfinding_visualizer
Path Finding Visualizer
This is a path finding visualizer application built using React and the Dijkstra algorithm. The application allows you to visualize how the Dijkstra algorithm finds the shortest path between two points on a grid.

Path Finding Visualizer

Features
Interactive grid where you can place start and end nodes, as well as walls to represent obstacles.
Real-time visualization of the Dijkstra algorithm, highlighting the nodes being visited and the shortest path found.
Adjustable speed control for the visualization, allowing you to slow down or speed up the process.
Reset button to clear the grid and start a new visualization.
Installation
To run the path finding visualizer on your local machine, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/path-finding-visualizer.git
Navigate to the project directory:

bash
Copy code
cd path-finding-visualizer
Install the dependencies:

bash
Copy code
npm install
Start the development server:

bash
Copy code
npm start
Open your browser and visit http://localhost:3000 to see the application running.

Usage
Click on any cell in the grid to place the start node. You can only have one start node at a time.
Click on another cell to place the end node. Similar to the start node, you can only have one end node at a time.
To place walls, click and drag the mouse across the grid. Walls represent obstacles that cannot be traversed by the algorithm.
Click the "Visualize" button to start the visualization. The algorithm will start finding the shortest path from the start node to the end node.
You can adjust the visualization speed using the speed control slider. Moving it to the left will slow down the visualization, and moving it to the right will speed it up.
To reset the grid and start a new visualization, click the "Reset" button.
Technologies Used
React: JavaScript library for building user interfaces.
Dijkstra Algorithm: A graph search algorithm used to find the shortest path between nodes in a graph.
