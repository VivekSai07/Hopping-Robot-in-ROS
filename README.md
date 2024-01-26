# Welcome to the Hopper Project for Gazebo using ROS Development Studio!

You will find all the code we generate for the Project tutorials in this repo.

Please feel free to comment and make any suggestions that you find relevant or fun to have.

## Video Tutorials

In this tutorial, you will find step-by-step how we got to have the code that you can find here.
The tutorials were created with the Web BAsed Online ROS development environment [ROSDevelopementStudio](http://www.theconstructsim.com/rds-ros-development-studio/).

 [Video-Tutorial-1-Create-RobotModel_Part1](https://www.youtube.com/watch?v=wgJG2Xp8FZA&t=1096s)
 
 
 ## To use the Jump Experimental Branch 
 You have to do the following:
 1) git clone https://github.com/leggedrobotics/xpp.git # You need some elements from here
 2) catkin_make # This will build some custom messages
 
# How to launch
You have to launch the simulation
```bash
$roslaunch legged_robots_sims main.launch
```

And the training launch
```bash
$roslaunch hopper_training main.launch
```
