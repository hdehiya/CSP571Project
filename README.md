# CSP571Project

# K-Means Clustering Analysis Report

This report presents a comprehensive K-Means clustering analysis performed on a dataset containing information about the adult U.S. population. The goal of the analysis is to uncover meaningful segmentation of the customer base by identifying distinct clusters with unique demographic and financial characteristics. 

The dataset was first preprocessed to prepare it for clustering. This involved identifying categorical and numerical features, implementing pipelines to handle encoding and scaling, and combining the preprocessing steps into a ColumnTransformer.

To determine the optimal number of clusters, both the elbow method and silhouette analysis were employed. These techniques indicated that a 3-cluster solution provided the best fit for the data.

The K-Means algorithm then assigned each data point to one of the three clusters, which exhibited the following key characteristics:

- Cluster 0 (Largest, 21,444 data points): Youngest average age, lowest average fnlwgt (final weight), lowest average education level, lowest average capital gain
- Cluster 1 (Second Largest, 25,261 data points): Oldest average age, highest average fnlwgt, highest average education level, highest average capital gain
- Cluster 2 (Smallest, 2,237 data points): Middle-range average age, lowest average fnlwgt, middle-range average education level, lowest average capital gain

The clustering results were validated using the silhouette score (0.122) and Calinski-Harabasz score (5561.468), confirming the validity of the 3-cluster structure.

Finally, a PCA-based visualization was created to provide a graphical representation of the distinct separation between the three identified customer segments.

In conclusion, the K-Means clustering analysis has revealed three unique groups within the adult population dataset, each with distinguishing demographic and financial characteristics. These insights can be leveraged by the business to develop targeted strategies, optimize product offerings, and enhance the overall customer experience.