# Reinforcement Learning - Q-Learning for FrozenLake

This Jupyter Notebook demonstrates the implementation of Q-learning to solve the FrozenLake environment provided by OpenAI Gym. In this environment, the agent's objective is to navigate a frozen lake, avoiding holes, and reaching the goal. The notebook employs a Q-table to learn the optimal actions for each state, making decisions that balance exploration and exploitation through epsilon-greedy exploration.

## Prerequisites

Before using this notebook, ensure you have the following prerequisites:

- Python (3.6+)
- Jupyter Notebook
- OpenAI Gym

You can install Gym using pip:

```bash
pip install gym
```

## Usage

1. Open this Jupyter Notebook using Jupyter Notebook or Jupyter Lab.

2. Execute each cell in the notebook to run the script step by step. 

3. The script will train a Q-table and display the learning progress, including cumulative rewards over episodes.

4. You can customize the following parameters in the script for tailored training:

   - `episodes`: The number of episodes for training.
   - `learning_rate_a`: The learning rate (alpha) for Q-learning.
   - `discount_factor_g`: The discount factor (gamma) for future rewards.
   - `epsilon`: The initial exploration rate (0-1).
   - `epsilon_decay_rate`: The rate at which epsilon decreases during training.
   - `is_training`: Set to `True` for agent training. Set to `False` to test the agent with a pre-trained Q-table.
   - `render`: Set to `True` to render the environment during training or testing.

## Customization

Feel free to modify the code in the notebook to experiment with different hyperparameters or adapt the Q-learning algorithm for other reinforcement learning tasks. Additionally, you can save and load Q-tables to avoid training from scratch when needed.

## License

This project is licensed under the MIT License.

## Acknowledgments

Special thanks to OpenAI Gym for providing the FrozenLake environment, enabling reinforcement learning experiments. Explore and customize this notebook for your own reinforcement learning projects.
