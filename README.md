# delivery-route-optimization
Developed a food delivery route optimization system in C++ using Dijkstra’s Algorithm to determine the shortest delivery path between locations. Modeled city routes as weighted graphs using an adjacency matrix and implemented logic for distance calculation and path reconstruction.
Overview

The Food Delivery Route Optimization System is a C++-based application designed to compute the shortest delivery routes in a city using Dijkstra’s Algorithm. The project models a city as a weighted graph, where nodes represent locations (restaurants, customers, or intersections) and edges represent the distance or time between these points. The system calculates optimal delivery paths to ensure minimal travel distance and faster delivery times.

This project also includes a frontend interface built with HTML and CSS, allowing users to visualize routes, input locations, and interact with the system in a structured and user-friendly way.

Features
>Shortest Path Calculation: Uses Dijkstra’s Algorithm to compute the minimum distance from a source location to any destination.
>Graph Representation: City locations are modeled using an adjacency matrix to represent weighted connections between nodes.
>Path Reconstruction: Provides clear step-by-step reconstruction of the shortest path for delivery.
>Interactive UI: Simple HTML and CSS-based frontend for inputting delivery points and visualizing routes.
>Cross-Platform: Works on Windows and Linux using GCC or Dev C++ compilers.
>Documentation & Git Integration: Well-commented code with version control using Git and GitHub for collaborative development.


Technologies Used:
>C++ – Core logic and implementation of Dijkstra’s Algorithm
>HTML & CSS – Frontend interface for route input and output display
>Graph Theory – Modeling city routes as weighted graphs
>Adjacency Matrix – Efficient storage and processing of graph connections
>GCC / Dev C++ – Compilation and execution environment
>Git & GitHub – Version control and collaborative development


How It Works:
Graph Setup: The city map is represented as a weighted graph using an adjacency matrix. Each node corresponds to a location, and each edge has a weight corresponding to the distance between two locations.
User Input: Users select the source location (restaurant) and destination (customer).
Shortest Path Calculation: The system runs Dijkstra’s Algorithm on the graph to find the shortest path.
Path Reconstruction: The application reconstructs the path from the source to the destination and calculates the total distance.


Output Display: 
The path and distance are displayed in a structured format on the frontend interface.
Installation
Clone the repository:
git clone <your-repo-url>
Open the C++ files in VS Code or Dev C++.
Compile and run the program using GCC or the IDE’s build system.
Open index.html in a browser to use the frontend interface for route visualization.
Usage.


Enter the number of locations and distances between them in the input section.
Select a starting location and the desired destination.
Click “Find Shortest Path” to compute the optimized delivery route.
The system displays the shortest path and total distance on the page.


Future Enhancements:
Integrate real-time map APIs like Google Maps for accurate route visualization.
Include dynamic traffic data for more realistic delivery time estimation.
Add multi-destination optimization to handle multiple orders in one route.
Improve frontend with interactive graph visualization using JavaScript libraries like D3.js.


Learning Outcomes:
Applied graph theory and algorithmic concepts in a practical scenario.
Strengthened C++ programming skills through logic implementation, testing, and debugging.
Gained experience in HTML/CSS integration for building simple user interfaces.
Learned version control with Git/GitHub for collaborative project development.
