# NetMagnet
Identification of influential users in social network using optimization algorithms.

## Description
The above code is implementing the Grey Wolf Optimization (GWO) algorithm for solving an optimization problem using the Independent Cascade Model (ICM). The purpose of this code is to optimize the selection of seed nodes in a social network in order to maximize their influence using the ICM.However, finding the influential nodes themselves is not the primary objective of this code. To find the influential nodes in a network, one can use centrality measures such as degree centrality, betweenness centrality, eigenvector centrality, or PageRank. These centrality measures can be computed using networkx, a Python library for working with graphs.Once the centrality measures are computed, one can identify the nodes with the highest centrality scores as the influential nodes in the network. This can be done by sorting the nodes by their centrality scores in descending order and selecting the top k nodes with the highest scores as the most influential nodes.

