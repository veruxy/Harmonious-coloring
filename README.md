# Harmonious-coloring
The scope of this project is to determine the harmonious chromatic number of a graph.
The project contains:
1. A sorce file for a program in C/C++:  harmonious_number.cpp
2. Two input files for the program: harmoniuos.in and harmoniuos_adj.in
3. 3 input file samples: graph_8.in, graph_10.in and graph_12.in containing the adjacent lists of all 3-regular graphs with 8, 10 and 12 vertices, respectively.

The program can take as input a graph given in file harmonious.in by the list of its edges or a lists of graphs with the same number of vertices given by adjacent lists, given in file harmoniuos_adj.in. These input files have the following structure:
harmonious.in: on  first line the number of vertices are given, then each of the next lines contain two numbers representing the extremities of an edge
harmonious_adj.in: on  first line the number of vertices  and the number of graphs are given, then the adjacent list for each graph in the following format (see graph_8.in for an example):
Graph x -> x is the number/name of the graph 
1   2 3 4  -> first number is the current vertex, next numbers are its neighbours
2   1 3 4 
3   1 2 5 
4   1 2 5 
5   3 4 6 
6   5 7 8 
7   6 9 10 
8   6 9 10 
9   7 8 10 
10   7 8 9 
