# Mini Project 4 - Machine Learning Course

This branch contains the materials and code for Mini Project 4 of the Machine Learning course taught by Dr. Aliyari at the Faculty of Electrical and Computer Engineering, K. N. Toosi University of Technology.

## Project Description

Mini Project 4 focuses on Reinforcement Learning (RL) and consists of two questions. One of the questions is chosen for implementation. The chosen question is Question 1:

### Question 1: Wumpus World

Wumpus World is a classic problem in AI and RL, involving a grid-based environment where an agent must navigate to find gold while avoiding hazards such as pits and the Wumpus.

#### Objectives:
- **Grid Navigation**: The agent must learn to navigate the grid efficiently.
- **Avoid Hazards**: The agent must learn to avoid pits and the Wumpus.
- **Collect Gold**: The agent must find and collect the gold.
- **Kill the Wumpus**: The agent can shoot an arrow to kill the Wumpus and eliminate it as a threat.

#### Environment Setup:
- **Grid Size**: A 4x4 grid where each cell can be empty, contain a pit, the Wumpus, or gold.
- **Action Space**: Move up, down, left, right. Shoot an arrow in any of the four directions (up, down, left, right).
- **Perceptions**: The Wumpus moves one cell in the direction of the action taken (optional).
- **Reward Space**:
  - +100 for getting the gold
  - -1000 for falling into a pit or being eaten by the Wumpus
  - +50 for killing the Wumpus (optional)
  - -1 for each move

#### Environment Definition:
- A 4x4 grid with random positions for pits, Wumpus, and gold. Define the initial state and possible states after each action.

#### Parameter Settings:
- **Learning Rate**: 0.1
- **Discount Factor**: 0.9
- **Exploration Rate**: Starts at 0.1 and decays over time

#### Tasks:
1. Implement Q-Learning and Deep Q-Learning for the Wumpus World environment.
2. Analyze cumulative rewards, average reward per episode, and the impact of the exploration rate on learning.
3. Compare the performance of Q-Learning and Deep Q-Learning.

### Files:
- mini_proj_4_40114624.ipynb: Jupyter Notebook for the implementation of Q-Learning.

**For any questions or further information, please contact e.ghasemi2@email.kntu.ac.ir**
