# Unsupervised_K-Means

K-Means: No Labelled data

1. Given some data points to different clusters.
2. Take initial Centriods(one from each cluster)
3. Calculate distance from Every data point to the centroids in each cluster using Euclidean or Manhattan distance.

![Alt text](https://github.com/srirampamerla/Unsupervised_K-Means/blob/main/k-means.png?raw=true)

4. Which Distance is less from three centroids and assign that datapoint to that particular cluster
5. Combine and avg the data points which belongs to same cluster then we will get new centroids
6. Again calculate the distance and which Distance is less from three centroids and assign that datapoint to that particular cluster
   Do all these steps untill old cluster and new clsuter are same.(Untill no change in the cluster)

![Alt text](https://github.com/srirampamerla/Unsupervised_K-Means/blob/main/k-means2.png?raw=true)

How to select k-value:
Using elbow methods we can find the optimized k-value

WCSS=Σ(distance b/w poins to nearest centroid)^2

we need to take the k value as wherever thre is no deprication in the graph(straight line after that point). We need to coinder that point.
