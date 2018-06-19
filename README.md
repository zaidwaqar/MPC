# MPC
Minimum Path Cover
Solution for the minumium path cover problem solved using Dijkstra’s Algorithm.

Getting Started
The program is written in C and can be compiled on any C compiler. You can also run the code on this Dev c.

It is based on greedy technique. The algorithm maintains a list visited[ ] of vertices, whose shortest distance from the source is already known.
 
If visited[1], equals 1, then the shortest distance of vertex i is already known. Initially, visited[i] is marked as, for source vertex.
 
At each step, we mark visited[v] as 1. Vertex v is a vertex at shortest distance from the source vertex. At each step of the algorithm, shortest distance of each vertex is stored in an array distance[ ]

# Sample Input:
5

0 10 0 30 100
10 0 50 0 0
0 50 0 20 10
30 0 20 0 60
100 0 10 60 0

0

# Sample Output:

Distance of node 1=10
path =1<-0
Distance of node 2=50
path =2 <- 3 <- 0
Distance of node 3=30
path =3 <- 0
Distance of node 4=60
path =4 <- 2 <- 3 <- 0

# Group Members
Muhammad Zaid Waqar 15B-057-SE
Sharukh Siddiqui 15B-050-SE
