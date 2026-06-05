# Customer Segmentation Using Clustering and Dimensionality Reduction

## Project Overview

This project applies unsupervised machine learning techniques to segment customers based on purchasing behaviour, customer value, demographics, and engagement metrics.

The objective was to identify meaningful customer groups that could support targeted marketing strategies, customer retention initiatives, and resource allocation decisions.

## Dataset

The dataset contained over 950,000 transaction records from a multinational e-commerce organisation operating across multiple continents.

Customer-level features were engineered to support segmentation analysis.

## Feature Engineering

The following customer-centric features were created:

* Frequency
* Recency
* Customer Lifetime Value (CLV)
* Average Unit Cost
* Customer Age

These features were aggregated at the customer level to create a single record per customer.

## Methods

### Exploratory Data Analysis

* Missing value assessment
* Duplicate value assessment
* Outlier investigation
* Distribution analysis

### Clustering

* K-Means Clustering
* Hierarchical Clustering

### Determining Optimal Clusters

* Elbow Method
* Silhouette Score
* Dendrogram Analysis

### Dimensionality Reduction

* Principal Component Analysis (PCA)
* t-Distributed Stochastic Neighbour Embedding (t-SNE)

## Key Findings

* Five customer segments were identified as the optimal clustering solution.
* Recency and age showed stronger discriminatory power between clusters than some other engineered features.
* t-SNE provided clearer visual separation between clusters compared with PCA.

## Key Skills Demonstrated

* Python
* Customer Analytics
* Feature Engineering
* Unsupervised Learning
* K-Means Clustering
* Hierarchical Clustering
* PCA
* t-SNE
* Data Visualisation
* Business Insight Generation

## Relevance to Healthcare and Drug Discovery

The same clustering techniques can be applied to:

* Patient stratification
* Precision medicine
* Clinical trial cohort identification
* Treatment response analysis
* Pharmaceutical market segmentation
* Population health analytics
