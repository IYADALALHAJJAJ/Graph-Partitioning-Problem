One example of a problem that is NP-hard but can be approached with heuristics, similar to the Traveling Salesman Problem (TSP), is the "Graph Partitioning Problem" (GPP). The Graph Partitioning Problem involves dividing the vertices of a graph into a specified number of subsets while minimizing the number of edges that cross between subsets.

Formally, given an undirected graph G=(V,E) and an integer k, the goal is to partition the vertex set V into k subsets V1,V2,…,Vk in a way that minimizes the number of edges between different subsets.

The Graph Partitioning Problem is known to be NP-hard, as finding an optimal partition is computationally challenging. However some approximation algorithms exist.

Design an algorithm to solve this problem in an efficient way and determine the computational complexity.
