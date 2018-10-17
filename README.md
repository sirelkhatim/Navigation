# README

## Project details

This project will implement a deep q network on the banana environment which contains the following:

		
- Vector Observation space size (per agent): 37  
- Vector Action space size (per agent): 4  

The environment is considered solved when the average score is above 13.

You can take the following actions in this environment

- 0 : move forward
- 1 : move backward
- 2 : turn left
- 3 : turn right


## Packages & Libraries
In order to run this code you will need the following packages from python3

- numpy
- random
- collections
- unityagents
- matplotlib
- torch (pytorch)

In order to install unityagents you can use pip install unityagents. 
You also need access to the banana environment. You can find details on how to install these in https://github.com/udacity/deep-reinforcement-learning/tree/master/p1_navigation .

## Files
In this project you have 3 main files
- Navigation.ipynb - jupyter notebook that contains the code to train and run the agent
- agent_dqn.py - Contains the code for the Q learning algorithm that uses Experience replay
- Model.py - Contains the code for the neural network used alongside the Q network.

## Motivation 
This motivation for this project is to build a deep Q network and train it on the banana environment.

## Instructions
After having installed all the dependencies above, you can just run the jupyter notebook
