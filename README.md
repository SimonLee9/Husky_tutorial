# Husky_tutorial

# Husky - Install

- sudo apt-get install ros-melodic-husky-desktop

- sudo apt-get install ros-melodic-husky-simulator

- export HUSKY_GAZEBO_DESCRIPTION=$(rospack find husky_gazebo)/urdf/description.gazebo.xacro

# Husky - running

- roslaunch husky_viz view_robot.launch
----
- roslaunch husky_gazebo husky_empty_world.launch

- roslaunch husky_gazebo husky_playpen.launch

- roslaunch husky_gazebo husky_empty_world.launch world_name:=worlds/willowgarage.world
