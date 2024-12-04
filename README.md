### Overview
K-Means is a popular and widely used clustering algorithm in unsupervised machine learning. It partitions a dataset into a pre-defined number of clusters, minimizing the variance within each cluster while maximizing the variance between clusters. This README provides a basic understanding of K-Means clustering, its applications, implementation, and usage.

### How K-Means Works
Initialization:
Select k initial centroids, which can be random or based on specific initialization methods like K-Means++.

Assignment:
Assign each data point to the nearest centroid based on a distance metric (commonly Euclidean distance).

Update:
Calculate the new centroids as the mean of the points assigned to each cluster.

Repeat:
Steps 2 and 3 are repeated until centroids stabilize (convergence) or a maximum number of iterations is reached.

Here you can see the scatterplot of the points together with their clusters colored (n_clu = 8). 

![Example Image](Figure1.png)

