# Customer Segmentation Using K-Means Clustering
## Project Overview
This project focuses on customer segmentation using the K-Means Clustering algorithm. The goal is to divide customers into distinct groups based on demographic and spending behavior. The insights generated from this analysis can help businesses tailor marketing strategies to better meet the needs of specific customer groups.

## Problem Statement
A retail store wants to understand its customers better by identifying patterns in their demographics and spending behavior. Using a dataset containing features such as age, annual income, and spending score, this project applies clustering techniques to segment customers into meaningful groups.

## Dataset
The dataset used in this project includes the following columns:

1. CustomerID: Unique identifier for each customer.
2. Gender: Gender of the customer.
3. Age: Age of the customer.
4. Annual Income ($): Annual income of the customer in dollars.
5. Spending Score (1-100): A score assigned by the store based on customer behavior and spending.
6. Profession: Profession of the customer.
7. Work Experience: Number of years the customer has worked.
8. Family Size: Number of family members.

## Data Preprocessing
Missing values were checked and handled.
Numerical features (Age, Annual Income ($), Spending Score (1-100)) were selected for clustering.
Features were standardized using StandardScaler for optimal performance of the clustering algorithm.
## Methodology
1. Elbow Method: 
The elbow method was used to determine the optimal number of clusters by analyzing the Within-Cluster-Sum-of-Squares (WCSS) for various cluster counts.

2. Silhouette Score: 
Silhouette scores were calculated for cluster counts ranging from 2 to 10 to validate the choice of the optimal number of clusters.

3. K-Means Clustering: 
The K-Means algorithm was applied to segment the customers into the optimal number of clusters based on the elbow method and silhouette score results.

4. Visualization: 
Clusters were visualized in 2D using scatter plots for better interpretability.

￼Enter
