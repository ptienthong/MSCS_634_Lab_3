# MSCS_634_Lab_3

## Lab Purpose
This lab explores clustering on the Wine dataset using K-Means and K-Medoids. It includes basic data exploration, z-score normalization, clustering, and evaluation with silhouette score and Adjusted Rand Index (ARI), plus PCA-based visualization.

## Key Insights and Observations
- K-Means produced better-defined clusters than K-Medoids based on the higher silhouette score and ARI.
- PCA plots show compact K-Means clusters, while K-Medoids exhibits slightly more irregular cluster shapes due to medoid constraints.

## Challenges
- `scikit-learn-extra` required `setuptools` to provide `distutils` compatibility under Python 3.13.