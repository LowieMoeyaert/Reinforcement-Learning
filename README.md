# Breakout Reinforcement Learning Project

---

## Project Overview

### Description
This project focuses on implementing a Deep Q-Network (DQN) to play the Breakout game from the OpenAI Gym environment. The goal is to train an agent using reinforcement learning techniques to achieve high scores in the game.

---

### Files and Folders

- **Breakout.ipynb**: Jupyter Notebook containing the main code for training and testing the DQN agent on the Breakout environment.
- **/video_dqn_breakout**: Folder containing a video of the trained DQN model playing Breakout.
- **/video_random_breakout**: Folder containing a video of random actions being performed in the Breakout environment.
- **DQN_Model.keras**: Serialized data file containing the trained DQN model.
- **Pipfile**: List of required Python packages for this project.
- **Pipfile.lock**: Lock file generated from Pipfile to ensure reproducibility of the environment.

---

### Approach

**Reinforcement Learning Setup:**
- **Environment:** Utilized the [Breakout environment](https://www.gymlibrary.dev/environments/atari/breakout/#breakout) from OpenAI Gym.
- **Agent:** Implemented a Deep Q-Network (DQN) using a neural network architecture to learn optimal strategies for playing Breakout.

**Training Process:**
- **Data Collection:** The agent interacts with the environment, and experiences (state, action, reward, next state) are collected.
- **Model Training:** Used the collected experiences to train the DQN model to approximate the Q-values of different state-action pairs.

**Evaluation:**
- **Testing:** Evaluated the trained DQN agent by running it in the Breakout environment and observing its performance.
- **Comparison:** Compared the performance of the trained DQN agent with that of an agent taking random actions.

---

### Results

The trained DQN model demonstrated significant improvement in playing Breakout compared to random actions. 
The video in `/video_dqn_breakout` showcases the agent's learned behavior and patterns in the game it recognised.
