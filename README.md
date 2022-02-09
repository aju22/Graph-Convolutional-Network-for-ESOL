# Graph-Convolutional-Network-for-ESOL

Lots of learning tasks require dealing with graph data which contains rich relation information among elements.
Modeling physics systems, learning molecular fingerprints, predicting protein interface, and classifying diseases
demand a model to learn from graph inputs. Graph neural networks (GNNs) are neural models that capture the dependence of graphs via message passing between the nodes of graphs. In
recent years, variants of GNNs such as graph convolutional network (GCN), graph attention network (GAT), graph
recurrent network (GRN) have demonstrated ground-breaking performances on many deep learning tasks.

![](https://perfectial.com/wp-content/uploads/2021/01/GNN-03-scaled.jpg)

# ESOL-Dataset

ESOL dataset is a regression dataset containing structures and water solubility data for 1128 compounds. The dataset is widely used to validate machine learning models on estimating solubility directly from molecular structures (as encoded in SMILES strings).

![](https://images.deepai.org/converted-papers/2006.06909/x1.png)

# Implementation

This implementation uses PyTorch Geometric for working with graph neural networks and RDKit as toolkit for visualising the chemical compounds. The notebook also has a little dive into the workings of graph neural networks and convolution/aggregation operations.

![](https://miro.medium.com/max/1400/1*vEd7QVWyJhy5jBkQ0McKgg.png)

# References

* Find a research paper : [Graph neural networks: A review of methods and applications](https://arxiv.org/ftp/arxiv/papers/1812/1812.08434.pdf)
* Find an amazing video by DeepMind which uses GNNs for predicting protein foldings: [AlphaFold: The making of a scientific breakthrough](https://www.youtube.com/watch?v=gg7WjuFs8F4)

