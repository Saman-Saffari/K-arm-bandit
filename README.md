# K-arm-bandit
# RL Assignment 1 – Bandit Algorithms

This notebook was developed for Assignment 1 in a Reinforcement Learning course. It focuses on the k-armed bandit problem and compares the performance of different learning strategies. The results are based on both stationary and changing reward distributions.

## What’s Covered

### Bandit Algorithms (Part 1 - Stationary)
- Greedy (always picks the best estimated arm)
- Epsilon-Greedy (explores randomly with some probability)
- Optimistic Initial Values (starts with high estimates to encourage early exploration)
- Gradient Bandit (uses softmax probabilities and preference updates)

### Changing Environments (Part 2 - Non-Stationary)
- Slowly changing means (drift)
- Mean-reverting environments
- Sudden change in reward values at a specific time step (abrupt shift)

## Running the Notebook

To run the experiments:
1. Open `RL1Project.ipynb` in JupyterLab or VS Code.
2. Run the notebook from start to finish.
3. All necessary libraries (like numpy and matplotlib) should already be available in most Python setups.

## Reproducibility

- Consistent master seed
- Random number generators for each bandit
- Fixed seeds used for drift and abrupt changes across all simulations

These steps ensure that the algorithms can be compared fairly and consistently.

## Included

- Code for all algorithms
- Plots showing average rewards and optimal action rates
- A separate report (submitted outside the notebook)

