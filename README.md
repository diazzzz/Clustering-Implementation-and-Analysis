# Kmeans-Implementation-and-Analysis

 
What is Clustering?

K-Means Clustering is a clustering algorithm and is considered to be an Unsupervised Learning technique.
It is used to divide a group of data points into clusters, where each point in the cluster is similar to each other.


Centroids

Simple: the center point of a cluster.
If K=3 (we want to find 3 clusters, then we would have 3 centroids, or centers, one for each cluster

Distance measures how similar two elements are and will influence the shape of the clusters.

To achieve accurate clustering, you need to:

1. Choose the right distance metric
2. Have good intuition behind your data


Distance → Dissimilarity

Smaller the distance → More Similarity BIGGER the distance → Less Similarity

Objective: To minimize total intra-cluster variance (e.g. Sum of Squared Error SSE)

Minimize Error: The error is the distance of each observation to the nearest cluster

Seperation: Observations in different clusters are dissimiliar to each other

❏ Homogeneity: Observations in the same cluster are similar to each other

❏ Find natural groupings

 Basic Steps for Clustering
 
● Preprocessing

○ Normalization/Standardization

● Distance/Similarity Measure

○ Similarity of two feature vectors

● Clustering Criterion 

○ Based on cost function

● Clustering Algorithms 

○ Based on clustering algorithm

● Validation/Interpretation


  Finding K - Elbow Method
  
GOAL: To identify when the set of clusters explains “most” of the variance in the data.

X - Number of Clusters
Y - Within SSE (Cumulative variance explained)

Since increasing K will always decrease our metric, the “elbow point” will allow us to see where the rate of decrease sharply shifts

We want to find the point where the distortion remains constant, even if we increase K further

In short...

The “ELBOW” is where the cumulative variance starts to FLATTEN OUT.

And adding in new clusters beyond this point only yields relatively small increase in variance.

Performance:

It is measured by checking the number of correct categorization in the cluster!!
   
 
 
 
 
 
 

