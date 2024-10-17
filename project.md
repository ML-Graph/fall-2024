---
layout: page
title: Project
permalink: /project/
---


## Node Classification
**(1) Homophily and Heterophily Analysis of Node Classification**
- Find and Download Datasets for Node Classification [dataset link](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.datasets.Planetoid.html)
- Calculate Homophily and Heterophily of different networks
- Code GNN-based models and obtain node classification performance
- Analyze the relationship between the homophily of a network/dataset and its corresponding node classification performance
  
**(2) Oversmoothing Analysis of Node Classification**
- Find and Download Datasets for Node Classification [dataset link](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.datasets.HeterophilousGraphDataset.html)
- Code GNN-based models and obtain node classification performance
- Change the Message-passing layer and obtain performance for each layer
- Analyze the relationship between the number of message-passing layers and the node classification performance
  
**(3) Node Classification on Heterogeneous Graphs**
- Find and Download Heterogeneous Graph Datasets for Node Classification [dataset link](https://pytorch-geometric.readthedocs.io/en/latest/notes/data_cheatsheet.html?highlight=heterogeneous)
- Code Heterogeneous GNN-based models and obtain node classification performance


## Link Prediction
**(1) Homophily and Heterophily Analysis of Link Prediction**
- Find and Download Datasets for Link Prediction [dataset link](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.datasets.Planetoid.html)
- Calculate Homophily and Heterophily of different networks
- Code GNN-based models and obtain link prediction performance
- Analyze the relationship between the homophily of a network/dataset and its corresponding link prediction performance
  
**(2) Degree Analysis of Link Prediction**
- Find and Download Datasets for Link Prediction [dataset link](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.datasets.Planetoid.html)
- Calculate Degree of different nodes within one network/dataset
- Code GNN-based model and obtain link prediction performance for a specific network
- Calculate the link prediction performance for each node and group nodes according to their degree in different groups
- Analyze the relationship between the average group link prediction performance and their average group degree

**(3) Implement LightGCN-based Recommender System and Compare its performance on users with different degrees/activity**
- Find and Download Datasets for the Recommender System [dataset link](https://github.com/kuandeng/LightGCN)
- Code LightGCN as your GNN-based recommender system and obtain recommendation performance for a specific network
- Calculate the recommendation performance for each user and group them based on user degree
- Analyze the relationship between the average group recommendation performance and their average group degree
- Read materials related to cold-start problems.

**(4) Implement LightGCN-based Recommender System and Compare its performance with and without text information**
- Find and Download Datasets for the Recommender System [dataset link](https://jmcauley.ucsd.edu/data/amazon/)
- Code LightGCN as your GNN-based recommender system and obtain recommendation performance for a specific network under two scenarios: with text and without text
- Calculate the recommendation performance for each user and group them based on user degree
- Analyze the relationship between the average group recommendation performance and their average group degree
- Read materials related to cold-start problems.

## Edge Classification
**(4) Compare Different GNN Models and MLP models on Edge Classification**
- Find and Download Datasets for the Recommender System [dataset link](https://jmcauley.ucsd.edu/data/amazon/)
- Process the review information for each customer-product interaction
- Code GNN to implement edge classification
- Calculate the performance and analyze the relationship between the edge classification performance with degree of ending points

## Graph Classification
**(5) Investigate the Imbalance Issue on Graph Classification**
- Find and Download Datasets for the Graph Classification [dataset link](https://pytorch-geometric.readthedocs.io/en/latest/generated/torch_geometric.datasets.TUDataset.html#torch_geometric.datasets.TUDataset)
- Calculate the number of graphs in different classes
- Code GNN to implement graph classification
- Change the number of training/validation/testing graphs to create balance and imbalance situations
- Train the GNN model, obtain graph classification performance on different imbalance ratios, and analyze their relationship.
  
**(6) Investigate whether incorporate 3D coordinates would help Graph Classification**
- Find and Download Datasets for Molecule Classification [dataset link](https://moleculenet.org/datasets-1)
- Code GNN to implement graph classification for 3D graphs
- Compare Graph Classification performance with and without 3D coordinates.
