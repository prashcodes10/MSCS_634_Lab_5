# MSCS_634_Lab_5

## Overview
This lab explores clustering techniques using **Hierarchical Clustering** and **DBSCAN** algorithms. The **Wine dataset** from `sklearn.datasets` is used to analyze the performance, parameter effects, and visualization of clusters. The lab emphasizes **practical understanding**, **evaluation metrics**, and **comparative analysis** of clustering algorithms.

## Objectives
- To perform **data exploration and standardization** for clustering suitability.  
- To apply **Agglomerative Hierarchical Clustering** and visualize cluster formation.  
- To apply **DBSCAN** and observe the effect of parameters `eps` and `min_samples`.  
- To evaluate clustering quality using metrics such as **Silhouette Score**, **Homogeneity Score**, and **Completeness Score**.  
- To compare strengths, weaknesses, and insights of Hierarchical vs. DBSCAN clustering.

## Key Findings
- **Hierarchical Clustering:**  
  - Nested clusters were observed and visualized via dendrograms.  
  - Sensitivity to parameter `n_clusters` was noted.  
  - Provides a structured hierarchy but can be affected by outliers and scaling.  

- **DBSCAN Clustering:**  
  - Dense regions were detected, and sparse points were labeled as noise.  
  - The choice of `eps` and `min_samples` strongly influenced cluster formation.  
  - Can detect clusters of arbitrary shapes but requires careful parameter tuning.  

- **Comparison:**  
  - Hierarchical clustering is better for understanding hierarchical relationships.  
  - DBSCAN is better for handling noise and discovering irregularly shaped clusters.  
  - Parameter tuning plays a critical role in the effectiveness of both algorithms.

## Challenges Faced
- DBSCAN produced all noise points when `eps` was too small, requiring adjustments.  
- Silhouette score calculation required careful handling of noise points to avoid errors.  
- Choosing optimal parameters for DBSCAN required experimentation and iteration.
