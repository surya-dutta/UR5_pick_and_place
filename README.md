# ThinkOutsideTheShell

"# UR5_pick_and_place" 

Simulated an autonomous pick-and-place and sorting capable robot in ROS and Gazebo using the Universal Robots' UR5 Robotic Arm, Robotiq85 Gripper, and a Kinect 3D Camera to perform the task of picking up objects, sorting them, and placing them at desired locations. Adopted the MoveIt interface for motion planning & collision avoidance of the arm in RViz, fetched camera data, applied the YOLOv5 object detection algorithm for extracting object positions, boundaries & confidence levels, interfaced object positions to the robot using ROS nodes, topics, & services, and then executed the pick-and-place and sorting tasks with an accuracy of 83.33%.
