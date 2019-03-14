# Autonomous-Object-Picker
Project - Autonomous Object Picker

Goal: To designed a Robotics Arm to Pick a desired colored object in a simulated environment decided by the user

Topic: Robotics- Kinematics and Dynamics of Robtic Arm

Software: V-Rep, Matlab, URDF

Implementation:
  * MATLAB and V-Rep are interfaced using Remote API for serial communication
  * Using a Camera the environment is scanned (in V-Rep) and using MATLAB the image is processed and the coordinates of the desired object is obtained
  * By knowing the coordinates, the inverse kinematics of the arm is computed in MATLAB and the joint values are sent to V-Rep to the robot
  * Used a Baxter gripper to pick the desired object
