# Data Structure -- 2 Shortest Path Algorithms

## Algorithms: 
	Bellman-Ford Shortest Path
	Floyd-Warshall Shortest Path

## Contents:   
	This program implements two 'shortest path' algorithms given a graph G
    of vertices connected by (u,v) edges. The Floyd-Warshall constructs a
	uxv matrix with each entry being the shortest distance from u to v.
	The Bellman-Ford algorithm is a single-source shortest path algorithm
	that calculates the shortest path from a source vertex s to every
	other other vertex in the graph. By implementing the single-source
	function on each vertex, it accomplishes the same as the Floyd-Warshall
	but not nearly as efficient.
	
## Author:
	David Weber

## Date:
	April 2017
	
## TO RUN THIS PROGRAM:
	1) Open Terminal/Command Prompt
	2) Navigate to folder containing bellmanford-floydwarshall.py (using cd commands)
	3) Type what is contained in these quotations: 
		"python bellmanford-floydwarshall.py -<both|b|f> input1.txt"
		
		4) You may also use input2.txt or edit either of the input files to create
			a graph of your choosing.
	
## Test cases:
	Here are some test cases for you to try, other than the default:
	
	1 3 2		1 2 3		0 1 2		8 7 1		
	4 8 0		4 8 0		4 5 3		6 0 2
	7 5 6		7 6 5		7 8 6		5 4 3
	
	The one below is impossible to solve, and the AI will evaluate every node (~100,000)
	before reporting failure.
	
	1 2 3
	4 5 6
	8 7 0



This program will show you the initialized matrix along
With the resulting matrix once the algorithm has been
executed. 

Run this program by typing in the terminal:

python assignment2.py -<both|b|f> input1.txt
