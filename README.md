
# 🍷 Unsupervised Clustering for Red Wine Chemical Composition Based Analysis

## Project Overview

In this project, we explore the chemical properties of red wine using unsupervised learning techniques to uncover hidden patterns and groupings within the data.
We apply multiple clustering algorithms after preprocessing and dimensionality reduction, and perform detailed cluster-level analysis to derive meaningful insights.

## 📚 Dataset Description
- Source: UCI Machine Learning Repository
- Dataset: Red Wine Quality Dataset
- Samples: 1599 observations
- Features: 11 physicochemical properties including:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Target: Wine quality (score between 0 and 10) – Note: Used only for post-clustering validation, not as part of clustering.

## 🔧 Project Steps
### 1. Feature Scaling and Transformation
Standardization of features was performed to ensure all variables contributed equally to the clustering process.

### 2. Dimensionality Reduction
Applied Principal Component Analysis (PCA) to reduce feature space while retaining most of the variance. PCA helps visualize data in 2D/3D and improves clustering performance.

### 3. Clustering Algorithms Applied
- K-Means Clustering
- DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
- Agglomerative Hierarchical Clustering
- Gaussian Mixture Models (GMM)

Each algorithm was tuned using appropriate metrics like silhouette scores, elbow method, and cluster visualization.

### 4. Cluster-Level Analysis
- Analyzed the characteristics of each cluster
- Average chemical properties per cluster
- Wine quality distribution within clusters
- Key differentiating features between clusters

Gained insights into how chemical composition correlates with wine groupings and quality levels.


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Authors

- [@NinadGawali](https://www.github.com/NinadGawali)
