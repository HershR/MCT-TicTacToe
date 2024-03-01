# Ultimate TicTacToe using MCT
Assignment from Game AI class

A bot that plays [Ultimate Tic-Tac-Toe](https://mathwithbaddrawings.com/2013/06/16/ultimate-tic-tac-toe/) 
using Monte Carlo Tree Search (MCTS).  
Ultimate Tic-Tac-Toe is a turn-based two-player game where players have to 
play a grid of 9 tic-tac-toe games simultaneously in order to complete one 
giant row, column, or diagonal. 
The catch is that each on each player’s turn, 
they can only place a cross or circle in one square of one board; 
and whichever square they pick, their opponent must play on the 
corresponding (possibly different) board.

# How to Run
## Player vs Player
`$ python p2_play.py human human `
## Player vs Vanilla MCT Bot
`$ python p2_play.py human mcts_vanilla` 
## Player vs MCT Bot with Heuristic
`$ python p2_play.py human mcts_modified` 

## Simulate
`$ python p2_play.py {bot_type1} {bot_type2}`

### Adjustable params
Feel free to change the following variable in mcts_vanilla.py and mcts_modified.py
- `num_nodes` number of simulations
