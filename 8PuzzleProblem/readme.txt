Assignment is implemented in Java.

Instructions for executing the program
1. Go to the src directory where sxa180065 folder is present.
2. Execute command javac sxa180065/*.java to compile the program
3. Execute command 
	java sxa180065/Main bfs to run BFS(Breadth First Search)
	java sxa180065/Main ids to run IDS(Iterative Deepening Search)
	java sxa180065/Main astar1 to run astar search with heuristic1
	java sxa180065/Main astar2 to run astar search with heuristic2
4. After executing the above command enter the input 3*3 board row by row separated by space in the command line.
	4 1 2
	6 3 *
	7 5 8
	Above is the example standard input to be taken.
5. Output will be displayed indicating number of states enqueued, total number of moves to reach the goal
and board sequences to reach the goal upon entering the input.