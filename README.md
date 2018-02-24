# TicTacToe-game
TicTacToe game where you can play versus the machine

The game was developped on Jupyter Notebook and may contain an import specific for it. It is written in Python 2.

To execute copy the file ipynb and paste it in Jupyter Notebook (Python 2 file). The code contains a final row where a Game object is created to start the game when executing the code.

The game consists on different classes representing each part of the game.

- Cells: objects representing each cell of the board that have an ID, a status and a owner

- Board: object that represents the whole board and it is composed by 9 Cells. It checks if someone wins, there is a draw and _ 
it provides with the best option to play in case there is a IA player

- Players: objects representing each player that has a play method that varies in fonction of Real / IA player (they are subclasses for Players)

- Game: an object that represents the game itself, it creates and interacts with the other objects in fonction of some parameters introduced as inputs
