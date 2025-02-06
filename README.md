# Taxi Route Optimization with Reinforcement Learning
![D9_20_059_1200](https://github.com/user-attachments/assets/2e54a0e7-ce82-45a6-b65a-64d59d82de0c)

## Project Description
Drive through the dynamic streets of a virtual city as a taxi driver in this exciting reinforcement learning project. Leverage Q-learning to optimize routes, ensuring passengers are picked up and dropped off efficiently. Train an RL agent to master the Taxi-v3 Gymnasium environment for seamless AI-driven transportation.

## Training, Evaluation & Visualization Steps
- First, we train an agent for 2,000 episodes using Q-learning, allowing a maximum of 100 actions per episode (`max_actions`). We record the total rewards from each episode and store them in a list called `episode_returns`.  
- Next, we extract the learned Q-values and save them in a NumPy array named `q_table`.  
- We then determine the learned policy and store it in a dictionary called `policy`.  
- To evaluate the agent, we test its learned policy in a single episode, initializing with a seed of 42. The encountered states from `env.render()` are stored as frames in a list named `frames`, while the total collected rewards are saved in `episode_total_reward`.  
- Finally, we execute the last provided cell to visualize the agent’s performance in navigating the environment effectively.
