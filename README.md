# Customer Segmentation using RFM Analysis and Clustering

## Project Overview
This project performs customer segmentation using RFM (Recency, Frequency, Monetary) analysis and clustering techniques. Three clustering algorithms—K-Means, Hierarchical Clustering, and DBSCAN—are compared to identify the most suitable model for segmenting customers based on their purchasing behaviour
## Dataset
Dataset: Online Retail II (UCI Machine Learning Repository)

* Time Period: December 2010 – December 2011
* Transactions: 500,000+
* Customers: 4,000+
* Domain: UK-based online retail
## Objectives
* Clean and preprocess transactional data.
* Perform exploratory data analysis (EDA).
* Generate RFM features for each customer.
* Apply multiple clustering algorithms.
* Compare clustering performance using evaluation metrics.
* Recommend business strategies for different customer segments.
## Methodology
1. Data Cleaning
2. EDA
3. RFM Analysis
4. Preprocessing
5. K-Means
6. Hierarchical Clustering
7. DBSCAN
8. Model Comparison
9. Business Recommendations

## Evaluation Metrics

* Silhouette Score
* Davies-Bouldin Index
* Calinski-Harabasz Index
  
### Clustering Model Comparison

| Metric | K-Means | Hierarchical | DBSCAN |
|---|---:|---:|---:|
| Silhouette Score ↑ | **0.34** | 0.28 | 0.21 |
| Davies–Bouldin Index ↓ | **1.01** | 1.13 | 2.02 |
| Calinski–Harabasz Index ↑ | **3313.12** | 2686.36 | 830.95 |

**Result:** K-Means achieved the best performance across all three clustering metrics and was selected with **4 clusters**. Hierarchical clustering also produced 4 clusters, while DBSCAN produced 3 clusters and identified **65 noise points**.

## Business Recommendations
* Reward high-value customers through loyalty programs.
* Encourage regular customers using personalized recommendations.
* Re-engage inactive customers with promotional campaigns.
* Target occasional customers using discounts and offers.
## Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-learn
* SciPy

## Project Visualizations

### Elbow Method

![Elbow Method](images/wcss_plot.png)

### Silhouette method

![Silhouette Method](images/sihouette_plot.png)

### K-Means Cluster Visualization

![K-Means](images/KMeans_PCA_visualization.png)

### DBSCAN Cluster Visualization

![DBSCAN](images/dbscan_clusters.png)
