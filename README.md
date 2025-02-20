# Smart-delivery-robot-AI
The Smart Delivery Robot project is a Python-based simulation designed to emulate an autonomous delivery robot navigating a user-defined environment. The robot is tasked with delivering parcels to specified locations while avoiding obstacles, no-entry zones, and adhering to one-way street constraints. This project incorporates the A* (A-star) pathfinding algorithm to efficiently determine the shortest and safest routes to delivery points. It was developed as part of a coursework assignment to demonstrate knowledge of autonomous agent behavior, environment modeling, and algorithmic decision-making.

Features

User-Defined Environment:
Select grid size (1–6).
Specify robot’s starting position.
Generate random delivery points, obstacles, no-entry zones, and one-way streets.
Autonomous Navigation:
Utilizes the A* algorithm for optimal pathfinding.
Robot automatically navigates to each delivery point while respecting environmental constraints.
Real-Time Visualization:
Visual display of the environment showing the robot’s location, delivery points, obstacles, and movement.
Clear visual feedback for delivered parcels and robot actions.
Error Handling & Input Validation:
Ensures valid user input for grid size and coordinates.
Avoids placement conflicts for obstacles and delivery points.
Project Structure

main() Function: Entry point of the program; handles user inputs and initiates the delivery process.
SmartDeliveryRobot Class: Contains methods for robot movement, delivery actions, and tracking progress.
find_shortest_path() Method: Implements the A* algorithm for route optimization.
display_grid() Function: Provides a visual representation of the grid environment.
How to Run

Ensure you have Python 3.x installed.
Clone this repository:
git clone <repository-link>
Navigate to the project folder:
cd smart-delivery-robot
Run the program:
python main.py
Usage Example

Enter the desired grid size (e.g., 5).
Specify the robot’s starting coordinates.
Observe the displayed environment with marked delivery points, obstacles, and restricted zones.
Watch as the robot autonomously navigates and completes deliveries.
Technologies Used

Python 3: Core programming language.
Heapq Library: Manages priority queues for the A* algorithm.
Random Library: Generates dynamic environments.
Time Library: Provides delays for step-by-step visualization.
Challenges & Solutions

Obstacle Avoidance: Implemented checks to prevent invalid robot moves.
Pathfinding Efficiency: Used the A* algorithm for faster and optimal route selection.
Environment Visualization: Created a clear grid display to track robot movements and deliveries.
Future Improvements

Implement graphical user interface (GUI) for enhanced visualization.
Add varying terrain costs to simulate real-world conditions.
Introduce battery management and charging stations for extended delivery simulations.
License

This project is developed for academic purposes. Redistribution or commercial use without permission is prohibited.
