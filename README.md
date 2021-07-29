# Run the arm of the robot on the Roz
**Operating the arm by [Roz Development Studio](https://www.theconstructsim.com/)**

* by 
```
$ roslaunch robot_arm_pkg check_motors.launch
$ roslaunch robot_arm_pkg check_motors_gazebo.launch
$ cd catkin_ws/src/arduino_robot_arm/robot_arm_pkg/scripts
$ sudo chmod +x joint_states_to_gazebo.py
$ rosrun robot_arm_pkg joint_states_to_gazebo.py
```
