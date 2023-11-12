# Crypto Clustering
### Contributor: Lan "Alice" Nguyen

### Overview
This project focuses on analyzing cryptocurrency data with the aim of employing Machine Learning techniques to categorize currencies based on their price fluctuations across diverse time intervals, ranging from the last 24 hours to the preceding 60 days.

### Analysis Steps
1. Data Preparation
- Load the cryptocurrency market data from the provided CSV file into a Pandas DataFrame.
- Normalize data using `StandardScaler()` function from `scikit_learn` library.

2.  Identifying Clusters in the Original Data
- Use the elbow method to find the optimal value for k (number of clusters).
- Apply the K-means algorithm to cluster cryptocurrencies based on the original scaled data.

3 Optimize Clusters with Principal Component Analysis (PCA)
- Perform PCA on original data, reducing features to three principal components.
- Construct a new DataFrame with the PCA data.
- Use the elbow method to identify the optimal value for k on the PCA-transformed data.
- Group the cryptocurrencies based on the PCA data

This analysis enables a nuanced comprehension of cryptocurrencies behavior. It makes it easier to organize and improve groups, leading to more insights.