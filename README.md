# Guidance-robot

This is a project for turtlebot based on [ROS](https://www.ros.org/).

It is hard for me to find the office location when I come into the CSE building of UCSD. I think it should be the same for every people when they come to a new environment. People may feel distressed and unhappy when they wandering off and cannot find the exact location of their destination. They are about to be late for their meetings!

We develop a Guidance robot to help this issue. 

## packages in ROS to be used
gmapping, amcl, 3dsensor, pocketsphinx, sound play，opencv

## How to launch our program?

Download the files in the src file of your ROS workspace

> catkin_make

> roscore

> roslaunch navigation find.launch

> rosrun navigation map_navigation_node

> rosrun new_project new_project

## Demo video
Here is the [demo video](https://drive.google.com/file/d/1UxDBCt74IqYm0Li7-sQCmeivUYO-Q_eM/view?usp=sharing)
