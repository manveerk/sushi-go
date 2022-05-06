Credits to https://github.com/Gravellent/sushigo-rl for creating a game playing implementation.

# SushiGo RL 

- State.py handles the logic of the game  
- Player package include a variety of agents that interacts with env. to play the game  
- utils.py contains many useful functions for the game, including the distribution of cards and score calculation  
- test.py offers some but not comprehensive unittests  
- For usage, check test.ipynb  
- # New Features:
- Added Q DB player that creates a q-table for state-value pairs in postgres
