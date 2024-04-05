# K-Means_Clustering_Algorithm_Python

### To demonstrate the K-Means i took a data-set of mall Customers and then Pre-Processed the data and Performed K-Means Clustering algorithm and then updated the Output in a new CSV file.

## Below i have mentioned Explanation for K-Means Clustering Algorithm

## Overview

K-Means is an unsupervised machine learning algorithm used for clustering unlabelled data, primarily in customer segmentation tasks. It identifies similarities between data points and groups them into clusters based on their features.

## Key Concepts

- **Clustering**: Grouping data points into clusters based on similarity.
- **Distance Metric**: K-Means typically uses the Euclidean distance metric to measure the distance between data points and centroids.
- **Number of Clusters (K)**: The hyperparameter that determines the number of clusters to be created.
- **Elbow Method**: A technique used to find the optimal value of K by analyzing the Within Cluster Sum of Squares (WCSS) values for different K values.

## Elbow Method

To find the optimal value of clusters using the elbow method, follow these steps:

1. **Execute K-Means Clustering**:
   - Run K-Means clustering on the dataset for different values of K (usually ranging from 1 to 10).

2. **Calculate WCSS**:
   - For each value of K, calculate the Within Cluster Sum of Squares (WCSS) value, which defines the total variations within a cluster.

3. **Plot WCSS vs. K**:
   - Plot a curve between the calculated WCSS values and the number of clusters K.

4. **Identify Elbow Point**:
   - Look for a sharp point of bend or an "elbow" in the plot.
   - This point represents the optimal value of K, where adding more clusters does not significantly reduce the WCSS.

## Usage

1. **Determining K Value**:
   - Use the elbow method to find the optimal value of K before applying K-Means clustering.

2. **Model Training**:
   - Initialize the K-Means model with the chosen value of K and fit it to the data.

3. **Evaluation**:
   - Evaluate the quality of clusters using appropriate metrics and techniques.
