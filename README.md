# Pirate Intelligent Agent  
_Reinforcement Learning with Q-Learning (Python, Jupyter, Keras)_

This project implements a reinforcement learning agent for a treasure-hunt style maze environment.  
A pirate-themed agent navigates through a grid-based maze, learning the optimal path to the treasure using the **Q-Learning algorithm**.

## Overview

The environment consists of:
- A grid-based maze
- Rewards for reaching the treasure
- Penalties or neutral states for other squares
- Predefined movement directions
- A winning goal state that ends the episode

My objective in this project was to develop and implement the **Q-Training algorithm** that teaches the pirate agent how to maximize its reward and find the optimal path to the treasure.

## Project Goals
- Implement an RL agent using Q-Learning  
- Train the agent to solve a navigation maze  
- Tune parameters such as learning rate, discount factor, and exploration rate  
- Validate that the agent improves over time (increasing cumulative reward)  

## How the Agent Works

1. The agent starts at a defined grid position.  
2. At each step, it chooses an action (up, down, left, right) using an ε-greedy policy.  
3. It updates its **Q-table** using the Bellman Equation:  

