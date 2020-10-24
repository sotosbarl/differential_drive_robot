# differential_drive_robot
diff_wheeled_robot_gazebo contains the gazebo launch files 
diff_wheeled_robot_control contains files for controlling the robot
mastering_ros_robot_description_pkg contains the urdf in which the robot is described


1)Put all three packages in catkin_ws/src
2) Do catkin_make
3) In two different terminals type subsequently:
    a) roslaunch diff_wheeled_robot_gazebo diff_wheeled_gazebo_full.launch (this will open gazebo with the model inside)
    b) roslaunch diff_wheeled_robot_control keyboard_teleop.launch   (this will enable keyboard-teleoperation)
