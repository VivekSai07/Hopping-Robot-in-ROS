# Welcome to the Hopper Project for Gazebo using ROS Development Studio!

You will find all the code we generate for the Project tutorials in this repo.

Please feel free to comment and make any suggestions that you find relevant or fun to have.

## Video Tutorials

In this tutorial, you will find step-by-step how we got to have the code that you can find here.
The tutorials were created with the Web Based Online ROS development environment [ROSDevelopementStudio](http://www.theconstructsim.com/rds-ros-development-studio/).

[Video-Tutorial-1-Create-RobotModel_Part1](https://www.youtube.com/watch?v=wgJG2Xp8FZA&t=1096s)

## Features:
- Realistic Simulation: The simulation environment accurately models the physics and dynamics of the hopping robot, providing a realistic testing ground.
- Modular Architecture: The project is structured with a modular architecture, making it easy to customize and extend for different experiments and research objectives.
- Training Framework: The training launch initializes the environment for reinforcement learning experiments, allowing users to train and optimize the hopping robot's control algorithms.
- Open Source: The entire project is open source, encouraging collaboration and contributions from the robotics community.
 
## To use the Jump Experimental Branch 
You have to do the following:
```bash
git clone https://github.com/leggedrobotics/xpp.git # You need some elements from here
catkin_make # This will build some custom messages
```

# How to launch
You have to launch the simulation
```bash
$roslaunch legged_robots_sims main.launch
```

And the training launch
```bash
$roslaunch hopper_training main.launch
```

## Contributions:
We welcome contributions from the community. If you find any issues or have ideas for improvement, please submit a pull request or open an issue on the GitHub repository.
