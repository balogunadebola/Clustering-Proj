# K-Means Clustering Analysis

This project demonstrates the application of K-Means clustering on a dataset with three features (A, B, and C). The goal is to identify natural groupings within the data and analyze the characteristics of each identified cluster.

## Project Steps:

1.  **Data Loading and Exploration:** The project begins by loading the dataset from a CSV file and displaying the initial rows to understand the data structure.
2.  **Feature Scaling and Dimensionality Reduction:** To prepare the data for clustering, the features are scaled using MinMaxScaler, and then Principal Component Analysis (PCA) is applied to reduce the dimensionality to two components for visualization purposes.
3.  **Visualizing Unclustered Data:** The data points are visualized in a 2D scatter plot based on the principal components to get a visual understanding of the data distribution before clustering.
4.  **Determining the Optimal Number of Clusters:** The Elbow Method is used by calculating the Within-Cluster Sum of Squares (WCSS) for different numbers of clusters (1 to 10). The WCSS is plotted against the number of clusters to identify the "elbow point," which suggests a suitable number of clusters.
5.  **K-Means Clustering:** Based on the WCSS plot, K-Means clustering is performed with a chosen number of clusters (in this case, 4). The model is fitted to the data, and cluster assignments are predicted for each data point.
6.  **Visualizing Clustered Data:** The clustered data points are visualized in a 2D scatter plot, with different colors and markers representing the assigned clusters.
7.  **Analyzing Cluster Characteristics:** The cluster assignments are added back to the original DataFrame. The data is then grouped by cluster, and the mean values for each feature are calculated for every cluster to understand their distinct characteristics.
8.  **Visualizing Cluster Characteristics:** A bar plot is generated to visualize the mean feature values by cluster, making it easier to compare and interpret the characteristics of each group.

This analysis provides insights into the inherent structure of the data and the distinguishing properties of each identified cluster.
