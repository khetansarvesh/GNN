# 1. Representation Learning
Our aim here is to convert the given graph into it's equivalent numerical vector representation!! Now there can be different types of graph and for these different types of graphs there are different representation learning techniques !!

- <ins> Numerical Graphs </ins> :
  Graphs made using numerical values only. Below we will see techniques used for *Undirected Numerical Graphs* but all these techniques are also applicable for *Directed Numerical Graphs*

  a. Numerical Graphs with only node features and no edge features : 
  - [Non Learning Based Methods](https://khetansarvesh.medium.com/introduction-to-graph-neural-networks-gnn-a145a81a81dc)
  - [Learning Based Methods](https://khetansarvesh.medium.com/graph-representation-learning-using-graph-convolution-attention-network-452732f69027)
  
  b. Numerical Graphs with both node features and edge features :
  - [Non Learning Based Methods]()
  - [Learning Based Methods]()
    

- <ins> Textual Graphs </ins> :
  Graphs made using text data only.

- <ins> Multimodal Graphs </ins> :
  - There are graphs made using different types of data e.g. text data / image data / numerical data.
  - You can simply convert text to its numerical representation and image to its numerical representation using any embedding model of that modal.
  - This will convert out graph into numerical graph and then we can use techniques discussed there to proceed further. 

# 2. Downstream Tasks
- Non Generative / Supervised Downstream Tasks
- Unsupervised Downstream Task - Clustering
  - Spatial Clustering
- Generative Downstream Task
  - Graph Variational Encoder (GVAE)
    a. [Video1](https://www.youtube.com/watch?v=ZyiW_ibeDGc)
    b. [Video2](https://www.youtube.com/watch?v=xoSU9aDSy4U)
    c. [Video3](https://www.youtube.com/watch?v=F45X7e6QS4E)
    d. [Code](https://github.com/deepfindr/gvae)
  - Graph Diffusion Models
   
# 3. Some other good resources
1. [GML 2023](https://github.com/xbresson/GML2023/tree/main)
2. [Pytorch Examples on GNN](https://github.com/pyg-team/pytorch_geometric/tree/master/examples)
