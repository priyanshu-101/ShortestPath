# ShortestPath

This is the Java program in command line arguement to find shortest distance between the two points.
The algo usded here is ijkstra algorithm


The Dijkstra algorithm is a shortest path algorithm used for finding the shortest path between two nodes in a graph. It is a greedy algorithm that works by maintaining a priority queue of unvisited nodes and repeatedly selecting the node with the lowest distance from the source node, updating the distances of its neighboring nodes, and marking the selected node as visited. The algorithm terminates when all nodes have been visited or when the destination node has been reached.

The algorithm uses the following steps:

Set the distance of the source node to 0 and the distance of all other nodes to infinity.
Create a priority queue of unvisited nodes and add all nodes to it.
While the priority queue is not empty:
a. Extract the node with the minimum distance from the priority queue.
b. For each unvisited neighbor of the extracted node:
i. Calculate the distance from the source node to the neighbor through the extracted node.
ii. If the calculated distance is less than the current distance of the neighbor, update the distance of the neighbor.
c. Mark the extracted node as visited.
The distance of the destination node is the shortest path from the source node to the destination node.
The Dijkstra algorithm is widely used in many fields such as computer networks, transportation systems, and geographic information systems. It can be used with both directed and undirected graphs, but it does not work with negative edge weights.

It is important to note that this is the ba
