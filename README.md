# ProblemSolvingAgentsPractice
Development of PSA for the chess knight problem over a 4x4 board
The problem consists of a general case of mxm (nxm even) where a piece is located in an arbitrary initial position from where it can only move in L shapes (classic chess knight movement). The objective is to go through all the indicated squares at the beginning and find the optimal order of movements for the knight so that it achieves both the path and the optimal decisions.
Classical tree search, such as breadth-first, depth-first, uniform-cost, and limited-depth-first, are used to compare the results and deduce which type of search yields better results for this problem, pondering run-time, number of steps, and algorithm complexity.

It also includes implementations of blind search using clever metaheuristics for A* and Greedy.

The purpose of this kind of exercise is to familiarize oneself with simple, fast algorithms that can be used for many problems that one might overlook and qualify as complex. But when broken down with a keen eye, it transforms into a much more approachable solution.
