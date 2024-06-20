# Fusion360 Robot Package

## Overview
This package contains a robot designed in Fusion 360, converted to URDF format using a plugin. The package includes files to launch the robot in RViz and Gazebo, and provides control via command velocity. It also simulates a laser range finder using YD LiDAR.

## Features
- Robot model created in Fusion 360
- URDF representation of the robot
- Launch files for RViz and Gazebo
- Command velocity control
- Simulated laser range finder using YD LiDAR


To launch in Rviz
roslaunch last_description display.launch

To launch in Gazebo
roslaunch last_description gazebo.launch

To control using cmd_vel
rosrun teleop_twist_keyboard teleop_twist_keyboard.py
