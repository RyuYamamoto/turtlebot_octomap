# 3D Mapping using Octomap on Turtle Bot
-----

## Install
### Install Octomap and Rtabmap  
```
$ sudo apt-get install ros-indigo-octomap ros-indigo-octomap-plugin ros-indigo-rtabmap ros-indigo-rtabmap-ros
```
### TurtleBot and TurtleBot3 Installation  
```
$ sudo apt-get install ros-kinetic-turtlebot* 
```

## Set up 
```
$ cd ~/catkin_ws/src
$ wstool init
$ wstool set turtlebot_octomap https://github.com/RyuYamamoto/turtlebot_octomap.git --git
$ wstool update turtlebot_octomap
```

## Run
### Turtlebot
```
$ roslaunch turtlebot_octomap turtlebot_build_map.launch
```

### Turtlebot3
```
$ roslaunch turtlebot_octomap turtlebot3_build_map.launch
```
