# PiSquare
This is a python template allowing two Raspberry Pis to play against each other in a variant of the classic game "dots and boxes". The game was used in the University of York Raspberry Pi challenge 2015.

The game is intended to give students a first taste of trying to develop an artificial intelligence. Their player receives information about the state of the game over a network socket and is required to respond with a valid move. The template includes a trivial but valid player that simply randomly chooses a move from those remaining. Programming a player with small improvements is straightforward (for example, adding the intelligence to spot when a square can be taken). Programming a strong player is very difficult, partly because the branch factor for dots and boxes is very high.

The rules follow those of the original dots and boxes, although the shape of the board is nonstandard (it forms the shape of a Greek letter pi rather than the standard rectangle). The original challenge specifications (and rules) used in the University of York challenge are included as a starting point if anyone else wants to run a similar competition. To encourage efficient programming, draws were resolved by the player with the fastest average move time being the winner. Scoring follows a "pie" theme.

Players need not run on a Raspberry Pi or in fact even be programmed in python. However, this was the setting for the challenge at York.

To run a game, three ingredients are needed:

1. A game server
2. Two players
3. A network connection between the Raspberry Pis running each player and the game server (not needed if all are running on the same Raspberry Pi - useful for development)

A video of the event at York (including another project-based challenge) is available [here](https://www.youtube.com/watch?v=CT_K9XD2YH0) and further details about the challenge are [here](https://www.cs.york.ac.uk/undergraduate/challenge/).
