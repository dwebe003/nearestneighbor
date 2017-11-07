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
	Here are the test cases contained in the input text files. The first row sets <# vertices> and <# edges>.
	Each row after that creates and edge from a vertex <s> to a vertex <t> with some <weight>.
	
	input1.txt:	
		4 5
		0 1 1
		1 2 -2 
		2 3 3 
		3 1 7
		3 0 4
	
	input2.txt:
		10 18
		0 5 3
		0 8 9
		1 6 9
		1 4 9
		2 3 3
		2 9 2
		3 9 3
		3 8 7
		4 5 5
		5 3 2
		5 6 9
		6 4 2
		7 0 6
		7 2 0
		8 3 8
		8 5 9
		8 4 3
		9 4 1

	Output:
		This program will show you the initialized matrix along
		with the resulting matrix once the algorithm has been
		executed. 
