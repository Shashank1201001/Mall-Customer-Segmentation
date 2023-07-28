Customer Segmentation with K-means
This repository contains an analysis of customer segmentation in a mall using the K-means clustering algorithm. The dataset comprises 200 samples, each with four attributes: gender, age, annual income, and spending score. The main goal of this analysis is to group customers into distinct clusters based on their annual income and spending score.
How to Determine the Number of Clusters?
To determine the optimal number of clusters, two methods have been employed:
1. Elbow Method:
The Elbow Method involves plotting the variance explained as a function of the number of clusters and identifying the "elbow" point where adding more clusters doesn't significantly reduce the variance. The optimal number of clusters is usually located at this elbow point.
2. Silhouette Method:
The Silhouette Method calculates the average silhouette score for different numbers of clusters. The silhouette score measures how well each data point fits into its assigned cluster. A higher average silhouette score indicates better-defined clusters.
After applying both methods, it was found that the optimal number of clusters for our dataset is 5.
Results and Insights
By segmenting customers into 5 clusters, we have labeled them as follows:
Cluster 1: Careless
Cluster 2: Standard
Cluster 3: Target
Cluster 4: Sensible
Cluster 5: Careful
Further, we have identified the Target customer segment. These customers exhibit specific behavior and preferences that can be utilized by the mall management to tailor marketing strategies and optimize customer experience for this high-potential group.
