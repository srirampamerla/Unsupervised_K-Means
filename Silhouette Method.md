# Silhouette Score 

The Silhouette Method or score is a measure of how similar a data point is within-cluster compared to other clusters

# s(i)=b(i)-a(i)/max{a(i),b(i)}

. S(i) is the silhouette coefficient of the data point i.

· a(i) is the average distance between i and all the other data points in the cluster to which i belongs.

· b(i) is the average distance from i to all clusters to which i does not belong.

Calculate the average_silhouette for every k. Average - silhouette =  s(i)/n

· The value of the silhouette coefficient is between [-1, 1].

. A score of 1 denotes the best, meaning that the data point i is very compact within the cluster to which it belongs and far away from the other clusters.

. The worst value is -1.

· Values near 0 denote overlapping clusters.

Which is highest point in the graph we need to select that.

![Alt text](https://github.com/srirampamerla/Unsupervised_K-Means/blob/main/silhouette.jpeg?raw=true)
