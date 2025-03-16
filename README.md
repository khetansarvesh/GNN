# 1. Representation Learning
Our aim here is to convert the given graph into it's equivalent numerical vector representation!! Now there can be different types of graph and for these different types of graphs there are different representation learning techniques !!

- <ins> Numerical Graphs </ins> :
  Graphs made using numerical values only. Below we will see techniques used for *Undirected Numerical Graphs* but all these techniques are also applicable for *Directed Numerical Graphs*
     
  a. Numerical Graphs with only node features and no edge features : 
  - [Non Learning Based Methods](https://khetansarvesh.medium.com/introduction-to-graph-neural-networks-gnn-a145a81a81dc)
  - [Learning Based Methods](https://khetansarvesh.medium.com/graph-representation-learning-using-graph-convolution-attention-network-452732f69027)
  
  b. Numerical Graphs with both node features and edge features :
  - [Learning Based Methods](https://khetansarvesh.medium.com/graph-representation-learning-using-graph-transformers-488ce1670469)
    

- <ins> Textual Graphs </ins> :
  - These are graphs made using text data only.
  - You can use any text embedding model to convert this graph into numerical graph
  - And then you can use techniques discussed in Numeircal Graph to get numeric representation of this graph!

- <ins> Multimodal Graphs </ins> :
  - There are graphs made using different types of data e.g. text data / image data / numerical data.
  - You can simply convert text to its numerical representation and image to its numerical representation using any embedding model of that modal.
  - This will convert our multimodal graph into numerical graph and then we can use techniques discussed there to get numerical representation of this entire graph. 

# 2. Downstream Tasks
- [Non Generative / Supervised Downstream Tasks]()
- Unsupervised Downstream Task - Clustering
  - Spatial Clustering
- [Generative Downstream Task](https://khetansarvesh.medium.com/generating-graphs-using-deep-learning-075466e23825)

   
# 3. Some other good resources
1. [GML 2023](https://github.com/xbresson/GML2023/tree/main)
2. [Pytorch Examples on GNN](https://github.com/pyg-team/pytorch_geometric/tree/master/examples)
