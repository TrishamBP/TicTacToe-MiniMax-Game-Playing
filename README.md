<div align="center">
  <h3 align="center">Enhanced Tic-Tac-Toe Game with Three Players: A Novel Approach to Extended Gameplay Dynamics and Winning Strategies</h3>
</div>

## Problem Statement
The traditional Tic-Tac-Toe game, a classic two-player game played on a 3x3 grid, has been a subject of extensive research in game theory and artificial intelligence. In this paper, we propose an extension of the traditional Tic-Tac-Toe game to accommodate three players, introducing a new coin 'T' alongside the traditional 'X' and 'O'. The game is played on a larger 6x6 grid, offering increased complexity and strategic depth compared to the original version. The objective remains the same: the first player to achieve four consecutive coins in a row, column, or diagonal wins the game. This paper presents the rules, gameplay mechanics, and winning strategies for the extended Tic-Tac-Toe game, along with a simulation of its working. We discuss the implications of introducing a third player and analyze the impact on gameplay dynamics, strategic considerations, and computational complexity. Furthermore, we explore potential applications of the extended Tic-Tac-Toe game in educational settings, cognitive development studies, and AI research.

![image](https://github.com/TrishamBP/TicTacToe-MiniMax-Game-Playing/assets/91331117/71a62f9b-c17d-4daf-9508-f1ac6fdd16e3)

## Adverserial Game Playing
Adversarial search, or game-tree search, is a technique for analyzing an adversarial game in order to try to determine who can win the game and what moves the players should make in order to win. Adversarial search is one of the oldest topics in Artificial Intelligence. The original ideas for adversarial search were developed by Shannon in 1950 and independently by Turing in 1951, in the context of the game of chess—and their ideas still form the basis for the techniques used today.

## Mini Max Algorithm
1. Generate the whole game tree.
2. Apply the utility function to leaf nodes to get their values.
3. Use the utility of nodes at level n to derive the utility of nodes at level n-1.
4. Continue backing up values towards the root (one layer at a time).
5. Eventually the backed up values reach the top of the tree, at which point Max chooses the move that yields the highest value. This is called the minimax decision because it maximises the utility for Max on the assumption that Min will play perfectly to minimise it.

![image](https://github.com/TrishamBP/TicTacToe-MiniMax-Game-Playing/assets/91331117/7fb89311-674c-4588-9d0b-4919a6cecfd8)

![image](https://github.com/TrishamBP/TicTacToe-MiniMax-Game-Playing/assets/91331117/90dfc760-93e6-418a-b1bd-57d72f43b999)


