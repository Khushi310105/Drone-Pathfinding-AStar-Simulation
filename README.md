#  Drone Pathfinding Simulation (A* Algorithm)

This project implements an AI-based drone navigation system that finds the most optimal path between a warehouse and a destination using the A* search algorithm. The simulation is visualized in real-time using Pygame.

---

##  Features
- Efficient pathfinding using A* algorithm
- Heuristic-based route optimization
- Real-time grid-based simulation
- Obstacle handling and shortest path calculation
- Interactive visualization using Pygame

---

##  Algorithm Used
The A* (A-star) algorithm is used to compute the shortest path by combining:

- g(n): Cost from start node to current node  
- h(n): Heuristic estimate from current node to goal  
- f(n) = g(n) + h(n)

---

##  Tech Stack
- Python
- A* Search Algorithm
- Pygame

---

##  How to Run

```bash
git clone https://github.com/<your-username>/Drone-Pathfinding-AStar-Simulation.git
cd Drone-Pathfinding-AStar-Simulation
pip install pygame
python main.py
