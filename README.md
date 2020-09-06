# ABB IRB140 ROS Simulation packages
This a set of ROS packages for simulating the ABB IRB140 robot, mainly for academic porpoises. Aimed to the students of Robotics in the the Universidad Nacional de Colombia.

Each package contains different functionalities, some of them require the use of the others packages, so its recommmended to download or install all of them as a whole.

# Installation
Run the following commands, currently only for ros-kinetic in ubuntu 16.04

```
cd ~/catkin_ws/src/
git clone https://github.com/GitSRealpe/abb_irb140_ros_sim.git
cd ..
catkin_make
```

# Running
There are two options or environments to simulate the robot, RViz and Gazebo
## RViz
Simply run `roslaunch abb_irb140_ros_sim irb140_rviz.launch`
## Gazebo
Simply run `roslaunch abb_irb140_ros_sim irb140_gazebo.launch`

**Author:** Sebastian Realpe Rua, mainly for use in the robotics lab of Universidad Nacional de Colombia

**With the help from:**

https://github.com/FreddyMartinez/abb_irb140_support as a good starting point, helped to reduce initial setup work.
