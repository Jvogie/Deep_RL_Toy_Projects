# Deep Reinforcement Learning Toy Projects

## Advantage Actor-Critic (A2C) in Robotic Simulations

This project involves training a reinforcement learning agent using the Advantage Actor-Critic (A2C) algorithm on various robotic simulation tasks provided by the panda-gym package. The goal is to teach a virtual robot to perform tasks such as reaching a point in space and picking and placing objects.

## Doom RL Training with Sample Factory

This Jupyter notebook demonstrates training a reinforcement learning agent in the "Doom" video game environment using the Sample Factory framework.

Features include:
- Training in the `doom_health_gathering_supreme` environment.
- Visualization of agent's performance post-training.
- Setup for ViZDoom engine and Sample Factory dependencies.
- Usage of custom neural network architecture for the Doom environment.

## Proximal Policy Optimization (PPO) algorithm in the Lunar Lander environment from OpenAI Gym

The notebook sets up the necessary environment for running a Proximal Policy Optimization (PPO) algorithm on the Lunar Lander game from OpenAI Gym. It installs system dependencies, sets up a virtual display for rendering the game, and imports required Python libraries. The notebook then initializes the game environment, runs a simple loop to take random actions in the environment, and resets it after termination or truncation. Further, it investigates the observation and action spaces to familiarize the user with the environment's inputs and outputs. The PPO model is then created with specified parameters, trained for one million timesteps, and saved. Finally, the notebook evaluates the trained model's performance on the Lunar Lander game and reports the average reward.
