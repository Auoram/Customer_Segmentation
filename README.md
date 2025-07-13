# Customer_Segmentation using Unsupervised Learning
This project applies unsupervised machine learning techniques to segment customers based on their features like Age, Gender, Annual Income, and Spending Score. It explores various clustering algorithms and visualizes the results to help understand customer groupings.

## Objectives
- Handle missing values and perform necessary preprocessing
- Visualize feature distributions and relationships
- Reduce dimensionality using PCA
- Apply and compare clustering algorithms:
  - K-Means
  - Agglomerative Clustering
  - DBSCAN
- Evaluate clustering using internal metrics (Silhouette Score, Davies-Bouldin Index)
- Analyze the effect of train/test splits on clustering performance

## Dataset
The dataset contains customer information such as:
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)
- City

## Algorithms Used
- **K-Means**: with Elbow method for optimal number of clusters
- **Agglomerative Clustering**: with dendrogram analysis
- **DBSCAN**: density-based clustering with noise detection

## Evaluation Metrics
- **Silhouette Score**
- **Davies-Bouldin Index**

## Conclusion
The project compares the performance of clustering algorithms across different train/test splits. K-Means was generally the most stable, while DBSCAN showed sensitivity to parameter choice and training size.
