# clustering
This project explores how different preprocessing techniques impact the performance of various clustering algorithms on the classic Iris dataset. It uses multiple evaluation metrics to compare clustering quality across methods.

Overview
We evaluate the performance of three clustering algorithms under six different preprocessing strategies using three internal clustering metrics. The entire process is automated and outputs a results table for easy comparison.

Algorithms Used
KMeans

Agglomerative Clustering (Hierarchical)

MeanShift

Preprocessing Techniques

Method	Description
No Processing	Raw data without modification
Normalization	Feature scaling using MinMaxScaler
Transform	Square root of absolute values
PCA	Dimensionality reduction to 2 components
T+N	Transform then Normalize
T+N+PCA	Transform → Normalize → PCA

Evaluation Metrics
Silhouette Score (higher is better)

Calinski-Harabasz Index (higher is better)

Davies-Bouldin Index (lower is better)
