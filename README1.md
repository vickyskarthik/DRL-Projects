# DRL-Projects
This is repo is based on Udacity's Nanodegree on Deep Reinforcement Learning

#Deep Q Network: Navigation
This project repository contains the code and references to implement a DQN for solving a navigation problem in Banana Simulator.

#About DQN
Q learning + Neural Network  = Deep Q Network 
In DQN we use Neural Network to approximate Q table.

#Environment details
The environment is based on Unity ML-agents.
Note: The project environment provided by Udacity is similar to, but not identical to the Banana Collector environment on the Unity ML-Agents GitHub page.

The agent is trained using Pytorch to navigate through the environment and  collect yellow bananas.  For every yellow banana the agent receives a reward of +1 and for every blue banana it receives a rewards of -1.  The agent is trained to avoid the blue banana as much as possible.

The state space has 37 dimensions and the action space has 4 actions each for  moving the four directions.

The task is episodic and the episode ends after achieving a reward of +13 over 100 consecutive episodes.

#Resources
A cheat sheet is provided by Udacity for studing reinforcement learning.
This repo has 3 code files – model.py, dqn_agent.py and Navigation.ipynb

#Getting started
#Installation requirements
The repository contains material related to Udacity's Deep Reinforcement Learning Nanodegree program.

Download the environment from one of the links below. You need only select the environment that matches your operating system:
Linux: click here[]
Mac OSX: click here[]
Windows (32-bit): click here[]
Windows (64-bit): click here[]

Place the file in the DRLND GitHub repository, in the p1_navigation/ folder, and unzip (or decompress) the file.
Instructions
Follow the instructions in Navigation.ipynb to get started with training your own agent!

