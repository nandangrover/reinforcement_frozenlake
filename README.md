<p align="center">
<img  alt="animatedgif.me" height="241px" width="241px" src="https://mlabonne.github.io/blog/images/qlearning/frozenlake.png">
</p>

<h3 align="center"> A Deep Dive into Reinforcement Learning: Q-Learning and Deep Q-Learning on a 10x10 FrozenLake Environment</h3>

## What we have built?
WUsing OpenAI gym, a FrozenLake v1 environment with a 10*10 board was successfully created. Deep Q-Learning was used to implement a neural network, which was then deployed for 10,000 episodes. While the agent was never able to obtain intrinsic rewards from the environment, we did observe reward progression for shaped rewards over time. Q-Learning was also used to power the game. To accurately assess the effectiveness of our custom algorithm in Q-Learning, we ran it in both scenarios, namely when the agent is aware of the reward location and when the agent is unaware of the reward location. We were able to see the agent consistently reaching the goal state after about half a million episodes of training using our enhancements to the standard Q-Learning method.

## Medium Article

https://medium.com/@nandangrover

## Running Locally


All the code for the reinforcement learning part is in the reinforcement directory. The code is written in Python 3.9. To install the required packages, run the following command in reinforcement directory:
```
pip install -r requirements.txt
```
