# Simulation-of-an-intelligent-system-in-an-hospital-environment
The goal of this project is to develop a system of three algorithms that control robots in a hospital setting. These algorithms are designed to optimize the robots' operations, specifically focusing on robot selection, robot finding, and robot charging.
# Environment
1) The first algorithm, the robot selection algorithm, aims to determine the most suitable robot for a given task. It considers factors such as the availability and proximity of the robots to the target location(one of 5 rooms ). By analyzing the availability and distance of each robot, the algorithm selects the robot that is both available and closest to the desired location. This ensures efficient utilization of the robots and minimizes unnecessary movement.
2) The second algorithm, the robot finding algorithm, focuses on determining the optimal path for the selected robot to navigate through the hospital to reach its destination. It employs pathfinding techniques, such as the A* search algorithm, to calculate the shortest path between the robot's current location and the target location. The algorithm considers the hospital layout, including obstacles, and computes the most efficient route for the robot to follow. By finding the optimal path, the algorithm reduces the time and energy required for the robot to reach its destination.
3) The third algorithm, the robot charging algorithm, is responsible for managing the charging process of the robots. It monitors the battery levels of the robots and ensures that they autonomously return to a designated charging station when their battery levels are low. The algorithm detects when a robot's battery level falls below a predetermined threshold and triggers the charging process. It calculates the path from the robot's current location to the charging station and guides the robot along the path to recharge its battery. This algorithm optimizes the robots' uptime and ensures they are always ready for operation.

![صورة1](https://github.com/user-attachments/assets/d1254e06-1526-4851-88b1-a61a266a0379)

Overall, this project combines these three algorithms to create an efficient and automated system for controlling robots in a hospital. The algorithms work in tandem to select the most suitable robot, guide it through the hospital using the shortest path, and recharge it when necessary. By implementing these algorithms, the system can enhance the productivity and effectiveness of the robot workforce in a hospital environment, facilitating various tasks such as transportation of goods and equipment, cleaning, and assistance to healthcare professionals.

# Results 

when it start ask to order room num to send robot to it and say in its way to you and choose best short path to arrive as shown with robot num

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/a52bcd88-d1d1-46c2-abc2-bfab2ff18204" />



another one order after little while so it find another available robot to send and choose best short path to arrive as shown with robot num

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/6d91d569-27b1-46f6-9d3d-a9697933aa98" />



when robot arrive to room ask patient for order place to get what he need as 

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/b9177b18-5bfb-4690-a668-d5ecb9de0402" />



and again robot select best short available path to place of order as 

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/c16ce3b6-5965-4c89-95f3-57f894921ccb" />



And also robot always calculate their battery power to save some for station charge path and notify that in station and when finish notify with available status waiting next orders


# Finally
This project is a simple simulation in a hospital with very limited capabilities. We hope to develop it to be closer to being realistic than imaginative and applicable to reality.


