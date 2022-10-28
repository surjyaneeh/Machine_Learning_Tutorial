# K-means Clustering
K distinct, non-overlapping subgroups (clusters), each containing a single data point, are sought after by the iterative Kmeans algorithm. It seeks to make the intra-cluster data points as comparable as feasible while maintaining the clusters as diverse (far) apart as possible. In order to minimize the sum of the squared distances between the data points and the cluster centroid, which represents the average value of all the data points in the cluster, it assigns data points to clusters in a particular pattern. As the degree of variance inside the cluster drops, the homogeneity (similarity) of the data points within the cluster rises.

### Here is how the k-means algorithm operates:

1. Indicate K, the number of clusters.

2. Initialize centroids by randomly choosing K data points for the centroids after shuffling the dataset first.

3. Continue iterating until the centroids do not change. i.e., the clustering of data points remains constant.

4. Add the squared distances between each data point and each centroid.

5. Connect every data point to the nearest cluster (centroid).

6. Calculate the centroids for each cluster by averaging all of the data points that are associated with it.
