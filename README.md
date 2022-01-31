# ROS Workspace for Tello projects

Build this workspace and enjoy if you have a DJI Ryze Tello drone. 

OS: Ubuntu 18.04

ROS 1

### Getting started with ROS and Tello drone
> roslaunch tello_driver tello_node.launch

### To fly drone with Controller (PS3 dualshock)
> roslaunch tello_driver joy_teleop.launch  

### Program 1: Tello AR tag follower
In this program, the tello drone follows an [Alvar ar tag](http://wiki.ros.org/ar_track_alvar)

To launch the program:
> rosrun tello_ar_detect follow_tag