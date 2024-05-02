# dynamixel_arm
ROS/ROS2 control package for open-manipulator-X robot (from Robotis), used for a ROS/ROS2 benchmarking.

I tried in those packages to remake with the simpliest way as possible the Open-Manipulator-X package from Robotis.
The aim was to make the same package with ROS(1) and ROS2, changing only the necessary features beetween ROS and ROS2 in order to compare their performances on a real usage on a Raspberry PI.

The packages are available with 2 branches:
- ros-noetic
- ros2-humble


You can find as submodules: 
- dynamixel_arm_control -> Control package for the robot.
- dynamixel_arm_description -> Package containing the URDF files, I took those made by Robotis.
- dynamixel_arm_moveit -> The moveit package in order to calculate the points.
- dynamixel_arm_msgs -> The msg package where I defined custom messages.
- dynamixel_arm_srv -> The srv package where I defined custom services.
