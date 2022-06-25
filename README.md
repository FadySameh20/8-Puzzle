# 8-Puzzle
This is a 8-puzzle program that aims to position each number in its correct position.

An instance of the 8-puzzle game consists of a board holding 8 distinct movable tiles, plus 
an empty space. For any such board, the empty space may be legally swapped with any tile 
horizontally or vertically adjacent to it. In this assignment, the blank space is going to be 
represented with the number 0. 
Given an initial state of the board, the search problem is to find a sequence of moves that 
transitions this state to the goal state; that is, the configuration with all tiles arranged in 
ascending order 0,1,2,3,4,5,6,7,8 . 
The search space is the set of all possible states reachable from the initial state. The blank 
space may be swapped with a component in one of the four directions ‘Up’, ‘Down’, ‘Left’, 
‘Right’, one move at a time. The cost of moving from one configuration of the board to 
another is the same and equal to one. Thus, the total cost of path is equal to the number of 
moves made from the initial state to the goal state.

Procedures:
1- The program will be asked to enter the puzzle that he wants to solve.
2- The program will check that the puzzle is valid (must consist of 9 digits) and that it is solvable (even inversions).
3- If the puzzle is valid, then the user will be asked to choose an algorithm from 3 algorithms (BFS, DFS, A*star has 2 heuristics functions: Manhattan distance and Euclidean distance).
