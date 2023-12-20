# snakeRL

## Description
snakeRL is an attempt at learning and utilizing reinforcement learning (pytorch) within a simple snake game. The snake game is the classic game where a snake attempts to eat an apple block and on doing so, grows in length. The snake is controlled normally using arrow keys. In this iteration, machine learning is used with the reinforcement learning technique to get the agent to learn to the play the game itself.

## Current Notes
* Currently, the the program plateaus at a high of 60 to 70 points.
* It's major issues are getting stuck spiraling into itself.
* I've experimented with penalties for idling and for time wasted, but it has only sped up the learning rate.
  - The goal was for the snake to prioritize the shortest path to the apples.
  - It hasn't been able to get past the local minima.

## Instructions
1. Clone this repository.
2. Set up a conda environment using python verstion 3.7.
3. pip/conda install the correct pytorch version, numpy, matplotlib, IPython
4. Run the command `python agent.py`.

Some helpful notes:
* Changing the `SPEED` variable in the `snake-ai.py` file can help speed up runs.
* Try experimenting with the rewards or penalties to see different results.

Updated: 12/19/23
