# Husky_tutorial

- https://github.com/husky/husky_robot

# Husky - Install

- sudo apt-get install ros-melodic-husky-navigation ros-melodic-husky-gazebo ros-melodic-husky-viz

- sudo apt-get install ros-melodic-husky-desktop

- sudo apt-get install ros-melodic-husky-simulator

- export HUSKY_GAZEBO_DESCRIPTION=$(rospack find husky_gazebo)/urdf/description.gazebo.xacro

# Husky - running

- roslaunch husky_viz view_robot.launch

---

- roslaunch husky_gazebo husky_empty_world.launch

- roslaunch husky_gazebo husky_playpen.launch

- roslaunch husky_gazebo husky_empty_world.launch world_name:=worlds/willowgarage.world

---

- roslaunch husky_navigation move_base_mapless_demo.launch

---

- roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
