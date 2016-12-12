# 3D Mapping using Octomap on Turtle Bot

Install
-----

Install Octomap and Rtabmap  
```
$ sudo apt-get install ros-indigo-octomap ros-indigo-octomap-plugin ros-indigo-rtabmap ros-indigo-rtabmap-ros
```

TurtleBot Installation  
```
$ sudo apt-get install ros-indigo-turtlebot ros-indigo-turtlebot-apps ros-indigo-turtlebot-interactions ros-indigo-turtlebot-simulator ros-indigo-kobuki-ftdi ros-indigo-rocon-remocon ros-indigo-rocon-qt-library ros-indigo-ar-track-alvar-msgs
```

Set up 
```
$ cd ~/catkin_ws/src
$ wstool init
$ wstool set turtlebot_octomap https://github.com/RyuYamamoto/turtlebot_octomap.git --git
$ wstool update turtlebot_octomap
```

Run
```
$ roslaunch turtlebot_octomap turtlebot_build_map.launch
```
