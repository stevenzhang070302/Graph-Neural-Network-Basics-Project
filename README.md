# Graph Neural Network Basics Project
 Getting to know Semi-Supervised Learning via Graph Neural Networks. Specifically, using Graph Neural Networks to map out social relationships within a Karate Club.

Name: Steven Zhang, Georgia Institute of Technology


# Project Overview
We build this project for the purpose of exploring GNN's or Graph Neural Networks for MATH 4804 (Math-Based Data Science). Our dataset is the Karate Club dataset which each individual in the Karate Club is a node on the graph and the relationships between each individual represents the edges and the strength of the relationships represents the length of the edges connected nodes in the graph. We utilize Pytorch, NetworkX, and Deep Graph Library in order to create a simple Graph Neural Network to ascertain which political side a person representing a node in the graph would take. The edges on the graph would represent the social connections between each of the individual nodes or people. Our graph neural network performs Node Classfication task as we want to determine which political side(2 sides or 2 labels) each one of the nodes or individuals belongs to. 

The [Karate_Club_GNN(Working).ipynb](https://github.com/stevenzhang070302/Graph-Neural-Network-Basics-Project/blob/main/Karate_Club_GNN(Working).ipynb) notebook contains the code and outputs for setting up a graph in NetworkX and building a Graph Neural Network. Our implementation of Graph Neural Network used Sage Convolution layers as the layers of our graph neural network. Our file contains the results performed by the Graph Neural Network, but also a comparison with a Clustering Method Spectral Clustering.


# Project Outcome
Below we can see some sample results of how the Graph Neural Network separated out the two political labels via a graph.

![Picture of a Graph of Karate Club Dataset](https://github.com/stevenzhang070302/Graph-Neural-Network-Basics-Project/blob/main/GNN_1.png)

![Picture of Intitial GNN Initialization](https://github.com/stevenzhang070302/Graph-Neural-Network-Basics-Project/blob/main/GNN_2.png)

![Picture of after GNN Executed](https://github.com/stevenzhang070302/Graph-Neural-Network-Basics-Project/blob/main/GNN_4.png)

Below we can see some sample results of how the Spectral Clustering Method separated out the two political labels via clustering.

![Picture of Results of Spectral Clustering](https://github.com/stevenzhang070302/Graph-Neural-Network-Basics-Project/blob/main/GNN_3.png)
