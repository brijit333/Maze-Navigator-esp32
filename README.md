 MAZE NAVIGATOR ESP32
 
 ![WhatsApp Image 2026-04-07 at 21 54 38](https://github.com/user-attachments/assets/fd426187-f172-4a44-852e-868e5b481b0d)

DESCRIPTION

Maze Navigator ESP32 is an intelligent autonomous robotic system designed to navigate and solve complex maze environments efficiently. Built using the ESP32 microcontroller, the robot utilizes IR sensors to detect paths and obstacles, enabling real-time decision making and adaptive movement.

The system is capable of identifying turns, avoiding dead ends, and selecting optimal paths using sensor-based logic and control algorithms. This project demonstrates practical implementation of embedded systems, robotics, and automation concepts, making it suitable for academic learning, competitions, and real-world navigation applications.

COMPONENTS USED

- ESP32
- IR Sensors
- L298N Motor Driver
- DC Motors
- Battery

WORKING

The Maze Navigator ESP32 uses the Flood Fill algorithm to efficiently solve the maze by determining the shortest path to the destination.
Initially, the maze is represented as a grid, where each cell is assigned a value based on its distance from the goal. The destination cell is given the lowest value, and surrounding cells are assigned increasing values.
The robot uses IR sensors to detect walls and open paths in real time. As it moves, it updates its knowledge of the maze and continuously recalculates the shortest path using the Flood Fill algorithm.

- The robot always moves to the adjacent cell with the lowest value.
- If a wall is detected, the algorithm updates the grid values dynamically.
- The robot explores the maze, updates distances, and refines its path.

Through this process, the robot gradually learns the maze and eventually finds the optimal path to reach the destination efficiently.

This approach ensures accurate navigation, adaptability to unknown mazes, and optimal pathfinding using embedded system logic.

<img width="660" height="900" alt="image" src="https://github.com/user-attachments/assets/c952a2d3-2139-48ac-925c-c6fd65afceec" />



DEMO VIDEO

https://drive.google.com/file/d/1kBhiW2tCx15ScLxTzwNshnd4mURk8ys3/view?usp=drivesdk


 
