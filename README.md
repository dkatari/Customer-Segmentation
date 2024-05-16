Objective: Segment customers based on purchasing behavior using K-Means clustering.
Data Source: Transaction records from an Excel file, preprocessed for missing values and outliers.
Key Metrics:
Recency: Days since the last purchase.
Frequency: Number of purchases.
Monetary: Total spending.
Data Processing:
Removed transactions with null Customer IDs.
Filtered out transactions with negative quantities and prices.
Converted invoice dates to datetime format.
Normalization: Applied MinMaxScaler to normalize Recency, Frequency, and Monetary values.
Optimal Clusters: Determined the optimal number of clusters (4) using the Elbow method and Silhouette scores.
Cluster Analysis:
Cluster 0: Best Customers - Recent, frequent, high spenders.
Cluster 1: Big Spenders - Moderately recent, high spenders, less frequent.
Cluster 2: Loyal Customers - Moderately recent, regular buyers with moderate spending.
Cluster 3: Lost Cheap Customers - Least recent, infrequent, low spenders.
Visualization: Created bar graphs to display average RFM values for each cluster.
Segmentation Map: Labeled clusters for targeted marketing strategies.
Output: Final segmented data ready for analysis and targeted marketing.
