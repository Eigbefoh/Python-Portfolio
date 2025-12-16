# Customer Segmentation with Clustering (K-Means + Validation)

This project builds a clustering-based customer segmentation framework for a global
e-commerce dataset (~952k transactions) to improve marketing efficiency and protect
revenue by identifying actionable customer personas — including high-value outliers.

- **Step 1** – Customer-level aggregation (transaction logs → customer profiles)
- **Step 2** – Feature engineering (RFM + CLV + Avg Unit Cost + Age)
- **Step 3** – Clustering + evaluation (Elbow + Silhouette → k = 5)
- **Step 4** – Validation + visualisation (Hierarchical clustering, PCA, t-SNE)

## Objectives

- Convert raw transactions into customer profiles suitable for targeting  
- Identify distinct segments for retention, win-back, and growth campaigns  
- Retain and understand “VIP” outliers rather than removing them as noise  
- Validate cluster quality and interpret segments into business actions  
