# Reinforcement_Learning

- Developed multiple agents to solve a maze environment using various reinforcement learning algorithms:
  - **Dynamic Programming (DP) Agent:** Implemented value iteration to find the optimal policy and value function.
  - **Monte Carlo (MC) Agent:** Utilized Monte Carlo methods to iteratively improve the policy and estimate the value function.
  - **Temporal Difference (TD) Agent:** Applied Q-learning with epsilon-greedy policy for online learning of the maze environment.

- Built and optimized a Deep Q-Network (DQN) to solve the CartPole-v1 environment in OpenAI Gym:
  - Designed a neural network with two hidden layers for the DQN.
  - Implemented epsilon-greedy policy for exploration and exploitation.
  - Used experience replay and target network updates to stabilize training.
  - Tuned hyperparameters including learning rate, replay buffer size, batch size, discount factor, and target update frequency.
  - Achieved significant performance improvements, demonstrating effective balance between exploration and exploitation.

- Tools and Technologies:
  - Python
  - PyTorch
  - OpenAI Gym
  - Matplotlib
  - NumPy
