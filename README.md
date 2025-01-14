# README

## Reinforcement Learning for Safe and Efficient Autonomous Merging Using Highway-Env
Assignment on the course Modelling and Simulation (MSc in Artificial Intelligence 1st year, 1st semester)

## A little context
### Overview
This project explores the application of Reinforcement Learning (RL) to optimize autonomous highway merging maneuvers using the Highway-Env framework. The research focuses on ensuring safety, minimizing traffic disruptions, and improving overall merging efficiency.

### Key Objectives
- Identify optimal merging speeds for autonomous vehicles.
  
- Determine the minimum safe gap between vehicles during merging.
  
- Identify the best action for the ego-vehicle while merging (braking or accelerating).
  
- Compare the behavioral strategies for the ego-vehicle on the highway (changing lanes or braking).
  
- Evaluate the impact of ego-vehicle actions on himself and others.

### Scenarios Studied
- What is the optimal merging velocity for the ego vehi-
cle?
- What is the minimum gap, highway vehicles should have
between them?
- What action should the ego vehicle take while on the
highway to minimize its own impact?
    - Should it brake and let the merging vehicle in?
    - Or would it be more effective to change lanes?
- What action should the ego vehicle take while on the
highway to minimize its impact on other vehicles?
    - Should it brake and let the merging vehicle in?
    - Or would it be more effective to change lanes?
- What is the best action for the ego vehicle to take during
merging to minimize its effect on other vehicles?
    - Should it brake close to the merging point?
    - Should it accelerate to enter the highway quickly

### The environment
#### For questions 1, 2 and 5
![scenario_3](https://github.com/user-attachments/assets/b5fa3751-f4a3-4097-b8d8-dd6d8d2bcd66)
#### For questions 3 and 4
![scenario_2](https://github.com/user-attachments/assets/d2a9eb33-b79a-43c5-bbb4-96b5f2196dd8)

## The repository includes:

**Notebook Folders**: Jupyter notebooks detailing different tasks of the project.

**README File**: This document summarizes the project objectives, structure, and instructions for using the code.

## Technologies Used

Framework: Highway-Env

Algorithm: Proximal Policy Optimization (PPO)

Libraries: Stable-Baselines3, PyTorch

Python version: 3.10.11

## How to run

Before running the code, it is necessary to install the required dependencies. All the necessary libraries are listed in the `requirements.txt` file. To ensure proper installation and avoid potential errors, PyTorch should be installed using the following command:

`pip install torch==2.3.1+cu121 torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121.`

Once all dependencies are installed, running the models will be straightforward. The project consists of 5 folders: one for statistics that analyze the results, and the others contain the code for all the trained models. To run the models, simply open the relevant jupyter notebook and execute all the cells to train the models and obtain the results.



## Future Work

- Integration with real-world traffic data.
  
- Exploration of multi-agent interactions.

- Refinement of reward functions for better adaptability.

- Testing in dynamic and complex environments.


