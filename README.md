# PingPongReinforcementLearning
This repository contains an implementation of Deep Q-Network (DQN) to train an agent to play Atari Pong using Deep Reinforcement Learning. The project follows the classic DQN algorithm introduced by DeepMind and includes improvements such as experience replay and target networks.

## Project Overview
The goal of this project is to train an AI agent to play Pong using Reinforcement Learning. The agent interacts with the environment, learns from rewards, and improves its gameplay over time.


## Key Features
- Uses OpenAI Gym for the Pong environment.
- Implements Deep Q-Network (DQN) for learning.
- Preprocesses frames (grayscale conversion, resizing, frame stacking).
- Implements experience replay for stable learning.
- Uses a target network to improve stability.
- Tracks training performance with reward plots.

## Project Structure
- dqn_pong.py – Main script to train the agent.
- model.py – Defines the neural network architecture.
- utils.py – Preprocessing functions for input frames.
- train.py – Training loop implementation.
- results/ – Stores training logs and plots.
