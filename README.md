How to use:
1. clone into src directory of an existing ROS workspace
2. catkin_make
3. roslaunch rover_gazebo rover_world.launch

change sonar angle:
`rostopic pub -1 Rover/joint_position_controller/command std_msgs/Float64 "data: 0.0"`
