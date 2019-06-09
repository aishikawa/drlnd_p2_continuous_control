This is a solution for project 2 of Udacity deep reinforcement learning. This repository based on [Udacity's deep-reinforcement-learning repository](https://github.com/udacity/deep-reinforcement-learning).

## Project Details
The purpose of this project is solving [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment.

### Environment
Double-jointed arm which can move to target locations. The agents must move its hand to the goal location, and keep it there.
- Observation space: 33 vaiables corresponding to position, rotation, and angular velocities of the arm. 
- Action space: 4 numbers corresponding to torque applicable to two joints. Every number in the action vector should be in (-1, 1)
- Reward: +0.1 is privided for each step that the hand is in the goal location.

For this project, we will provide you with two separate versions of the Unity environment:
- The first version contains a single agent.
- The second version contains 20 identical agents, each with its own copy of the environment.

I used the second version.

### Solving the Environment
Our agent must get an average socore +30 over 100 consecutive episodes, and over all agents.

## Getting Started

#### Create Python environment
Clone [this repository](https://github.com/udacity/deep-reinforcement-learning), and follow the [instructions]() to set up Python environment.

#### Download the Unity Environment
Download the environment from one of the links below.  You need only select the environment that matches your operating system:
- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)

Then, place the file in the `reacher/` folder.

#### Instructions
Activate the python environment and run main.py
```
python main.py > out.txt
```
 