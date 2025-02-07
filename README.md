# Delhi Metro CUI-Based Application

## Overview
This is a Command Line Interface (CUI) based Delhi Metro application developed in Java. The application leverages graph data structures, heaps, and algorithms like Dijkstra's, DFS, and BFS to provide metro-related functionalities such as listing stations, finding routes, and fare calculation.

## Features
- **List All Stations**: Displays a complete list of all Delhi Metro stations.
- **Find Routes**: Computes and displays the shortest path between two stations using Dijkstra's Algorithm.
- **Fare Calculation**: Determines the fare based on the selected route.
- **Graph-Based Navigation**: Uses DFS and BFS for traversal and exploration of the metro network.

## Technologies Used
- **Java**
- **Graphs & Heaps**
- **Dijkstra's Algorithm**
- **Depth-First Search (DFS)**
- **Breadth-First Search (BFS)**

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/tejasvi001/delhiMetroApp.git
   ```
2. Navigate to the project directory:
   ```sh
   cd DelhiMetroApp
   ```
3. Compile the Java files:
   ```sh
   javac Main.java
   ```
4. Run the application:
   ```sh
   java Main
   ```

## How It Works
1. The user is prompted to enter a source and destination station.
2. The program finds and displays the shortest route using Dijkstra’s algorithm.
3. The fare for the journey is calculated and displayed.
4. Users can explore all stations or traverse the metro map using DFS/BFS.

## Future Enhancements
- Implement a GUI for better user interaction.
- Integrate live metro updates.
- Add multi-line fare calculations.

## Contributing
Feel free to fork the repository and submit pull requests for improvements and bug fixes.

## License
This project is licensed under the MIT License.

---
Made with ❤️ in Java

