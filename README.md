# ROS2 and TurtleBot Robotics simutation
This README is a compilation of all basic tasks and learnings from the ROS2 workshop for simulation and control of Turtlebot and ROS2 robotics simulation 

# Basic Linux Terminal Commands
  - ```ls```:Used to list the subdirectories
  - ```cd```:Used to access a directory
  - ```mkdir```:Used to create a new directory
  - ```touch```:Used to create a new file
  - ```rm```:Used to remove/delete a file form selected directory
  - ```rmdir```:Used to remove/delete the selected directory
  - ```cp```:Used to copy directories or files
  - ```ctrl```+```shift```+```O```:Opens a new terminal tab(multiple windows)

# Intorduction to ROS2
  * Topics covered are basic ROS2 architecture and commands
    - ```ros2 topic```
    - ```ros2 node```

# Creating a package in ROS2
  * Created a ROS2 package using the colcon build tool ```sudo apt install``` &```colcon-build```
  * Added a Python script within the created package
  * Drew a circle using the package in VS code
<p align="center"> <img src="./img ROS/tsim png git.png">

#Launching Gazebo Simulation and controling the bot
  *Used ```ros2 launch turtlebot3_gazebo turtlebot3_world.launch.py``` to launch a gazebo simulation with obstacles and a bot
<p align="center"> <img src="./img ROS/rosobjects.png">
  
  *Used ```ros2 run turtlebot3_teleop teleop_keyboard``` to use the keyboard WASD to move the 
   bot

# Using the Rviz to map the Gazebo environment

 * Used ```ros2 launch turtlebot3_navigation2 navigation2.launch,py use sim_time:=True```
  to open Rviz and move the bot around using ```teleop``` to map the environment
<p align="center"> <img src="./img ROS/git1.jpg"> 

 unfinished map

<p align="center"> <img src="./img ROS/git2.jpg">

finished map

  

  

