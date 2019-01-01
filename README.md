# Repo-Navigation-Project1


Project 1: Navigation

##Introduction

For this project, you will train an agent to navigate (and collect bananas!) in a large, square world.

Trained Agent

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

0 - move forward.
1 - move backward.
2 - turn left.
3 - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

##Getting started

1. Download or clone the complete repository Repo-Navigation-Project1 from Github onto a Windows environment. The repository contains two folders:
- p1_navigation: Contains the main file, Navigation.ipynb running the model as well as the bananas unity executable for a Windows environment
- python: Contains the unity support files necessary to run the unity applications

2. Create a virtual environment using Anaconda prompt 
(for windows environment) 
>conda create --name drlnd python=3.6 
>activate drlnd

3. Install the files in the requirements.txt file:
>conda install --yes --file requirements.txt

##Instructions

4. Navigate to the Repo-Navigation-Project1
 directory and type Jupyter Notebook

5. Navigate to the p1_navigation directory

5. Open the Navigation.ipynb with Juyter Notebook and run each of the cells in the file. Sequentially press run on each of the blocks of code. 
This will load the environment, set up the action value network, explore the environment and gradually learn until the average score is 13.
The function performing learning over sequential episodes is dqn(). 



