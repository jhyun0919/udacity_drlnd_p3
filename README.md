This project is one of the projects from [Udacity Deep Reinforcement Learning Nano-degree](https://github.com/udacity/deep-reinforcement-learning).

Following is the process and results I have done.

---

# Project Details

![](https://user-images.githubusercontent.com/10624937/42135623-e770e354-7d12-11e8-998d-29fc74429ca2.gif)

## The environment

For this project, we will work with the [Tennis](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#tennis) environment.  

In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.  

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.


## Solving the environment

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

* After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
* This yields a single _score_ for each episode.  


**The environment is considered solved, when the average (over 100 episodes) of those _scores_ is at least +0.5.**

# Getting Started

## Step 1: Clone the Repository

To clone this git repository, put a following commandline.

```
$ git clone https://github.com/jhyun0919/udacity_drlnd_p3.git
```

## Step 2: Download the Unity Environment

For this project, you need to download the Unity Environment from one ot the links below.

* [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
* [Linux (headliss ver.)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux_NoVis.zip)
* [OSX](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
* [Windows (32-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
* [Windows (64-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)

After download it, you need to place the file in the root directory of this project repository.

## Step 3: Set virtual environment for this project

The project dependency is listed in [requirements.txt]().  
The dependency can be met with the following command:

```
$ pip install -r requirements.txt
```

# Solutions

You can check out about the description of the implementation & results of the experiment on this project in [Tennis.ipynb]() & [Report.ipynb]().

