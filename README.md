[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/oxMPd-Kw)

> In this lab, we went through the full simulation process of a Panda robot arm using the Python Robotics Toolbox:
 + First, the robot model is initialized and the kinematic parameters are set based on the results of Lab 1.
 + Then, we configure a random starting pose and solve the forward kinematics problem to determine the terminal position.
 + The workspace of the robot is constructed by sampling joint configurations within a given range. (first 5 joint)
 + A specific point in the workspace is selected and the inverse kinematics problem is solved to find the corresponding joint configuration.
 + Next, we plan the motion between the initial and final pose using three methods: jtraj, mtraj(quintic), and mtraj(trapezoidal).
 + The results are visualized through graphs of position, velocity and acceleration of each joint.
> Comparing the methods shows that jtraj and quintic produce very smooth motion with constant acceleration, while LSPB is simpler but less smooth due to abrupt acceleration changes at phase transition points. The experiment helps me understand the differences between trajectory planning algorithms and their impact on the smoothness and controllability of the robot.