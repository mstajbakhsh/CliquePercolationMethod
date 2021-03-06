# CliquePercolationMethod
Clique Percolation Method (CPM) is a gephi plugin for finding overlapping communities. This method is used for finding overlapping communities, firstly by detecting communities of size k, then forming a clique graph based of cliques of size k. This plugin is designed to work with Gephi and will transform a graph to the clique graph of size k.

# Algorithm
The algorithm is simple:

1- first find all cliques of size k in the graph
2- then create graph where nodes are cliques of size k
3- add edges if two nodes (cliques) share k-1 common nodes.
4- each connected component is a community

# Reference
Palla, Gergely, Imre Derényi, Illés Farkas, and Tamás Vicsek. "Uncovering the overlapping community structure of complex networks in nature and society." Nature 435, no. 7043 (2005): 814-818.
