Customer Segmentation using Interpretable Machine Learning
This project focuses on identifying and interpreting customer segments using unsupervised machine learning techniques, primarily K-Means Clustering, enriched with interpretable AI methods like SHAP and LIME.

Objective
To group customers based on their demographic, behavioral, and spending attributes in order to generate actionable insights for:

Targeted marketing

Personalized offers

Customer retention

Churn prediction

Dataset
Source: Marketing campaign dataset from a retail company

Records: 2,240 customers

Features: 29 (including demographics, spending habits, campaign responses, web activity)

Techniques & Tools
Preprocessing: Missing value imputation, outlier removal (IQR method), one-hot encoding, feature scaling (MinMax)

Feature Engineering: Age, total spend, customer tenure, campaign engagement, children at home

Clustering:

Algorithm: K-Means (selected based on Elbow Method & Silhouette Score ~0.51)

Cluster evaluation: Elbow Method, Silhouette Analysis

Visualization: PCA, t-SNE, scatter plots, heatmaps, boxplots

Interpretability: SHAP & LIME (explaining feature contributions to cluster assignments)

Key Outcomes
4 Distinct Clusters Identified:

Cluster 1: High-income, high-spending, loyal buyers

Cluster 2: Young, digitally active, responsive to campaigns

Cluster 0: Budget-conscious families with children

Cluster 3: Older, low-engagement customers

Business Recommendations:

Reward loyalty with exclusive offers (Cluster 1)

Focus digital marketing on Cluster 2

Offer family discounts to Cluster 0

Re-engage Cluster 3 via newsletters and offline promos

Technologies Used
Python

Scikit-learn

Pandas & NumPy

Matplotlib & Seaborn

SHAP, LIME (for interpretability)

Jupyter Notebook

Future Scope
Explore alternative clustering techniques like DBSCAN, Gaussian Mixture Models

Integrate a live dashboard for marketing teams

A/B test cluster-specific marketing strategies

Time-series behavior modeling

