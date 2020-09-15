# SPS-3243-Wall-following-Robot-Simulation-using-AWS-RoboMaker
Wall following Robot Simulation using AWS RoboMaker

Technologies for autonomous robots and self-driving cars have been rapidly advancing. Their development often relies on building application-specific simulation environments, and using the information to train reinforcement learning (RL) models.
An RL algorithm will help navigate the agent to reach to the GOAL without bumping into a wall. The agent has a 360-degree surround lidar scanner (360 points x 5 fps) so that it monitors the distance from the surrounding walls all around. The lidar data are used to describe a state at a given step within an episode. The agent makes a decision out of 5 different actions i.e. turn left, turn right, move straight, steer to the left, and steer to the right.
