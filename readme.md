# Udacity Tennis Project
DDPG Agent solving Unity Tennis Environment

## Environment Info

- `Number of agents: 2`<br>
- `Number of actions: 2 Continuous (Moving Away/Closer to Net and Jumping)`<br>
- `State Length : 24 (For Each Agent)` <br>
- `Environment Solved: 1303 episodes (avg 0.50)`

## Reward Function
In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

## Benchmark 
Reward from each agent is added without discounting and max award (from both agents) is set as episode reward<br>
The problem is considered solved when the agents achieve average reward of 0.50+ over 100 consecutive episodes


## Requirements Linux/Mac/Windows

- python 3.6
- `virtualenv` set up

## Setup
### Linux

- Clone the repository
- Run `python3 -m pip install -r requirements.txt`
- Run `unzip Tennis_Linux.zip`
- Check `solutions.ipynb` notebook for solution

### Windows/Mac

- Clone the repository
- Download appropiate env from here : [Environment](https://github.com/udacity/deep-reinforcement-learning/tree/master/p3_collab-compet#getting-started)
- Replace executable path of downloaded env in `main.py and solutions.ipynb files`
- Run `python3 -m pip install -r requirements.txt`
- Check `solution.ipynb` notebook for solution

## Play Agent

- Run `python3 main.py`

### [Report](./report.md)
