# Unsupervised Learning

**Unsupervised Learning** is a type of machine learning where the program learns 
the inherent structure of the data based on unlabeled examples.

An example of this includes **clustering**, wich is a common unsupervised 
machine learning approach that finds patterns and structures in unlabeled data 
by grouping them into clusters.

Some examples:

- Social networks clustering topics in their news feed
- Consumer sites clustering users for recommendations
- Search engines to group similar objects in one cluster

## K means 

## Hierarchical clustering 

In *complete* linkage, the distance between clusters is the distance between 
the furthest points of the clusters. In *single* linkage, the distance between 
clusters is the distance between the closest points of the clusters. 

This means different linkage, different hierarchical clustering!

# Supervised Learning

When we explicitly tell a program what we expect the output to be, and let 
it learn the rules that produce expected outputs from given inputs, we are 
performing **supervised learning**.

1. **Supervised Learning**: data is labeled and the program learns to predict
the output from the input data

2. **Unsupervised Learning**: data is unlabeled and the program learns to 
recognize the inherent structure in the input data

# Case study 

In order to illustrate a clustering analysis, we used human breast mass data coming from [the UIC machine learning repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)) with 


- Ten features measured of each cell nuclei
- Summary information is provided for each group of cells
- Includes diagnosis: benign (not cancerous) and malignant (cancerous)

