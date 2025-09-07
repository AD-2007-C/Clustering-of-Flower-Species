# Clustering-of-Flower-Species
This project explores two popular clustering algorithms – K-means and DBSCAN – applied to the Iris dataset.
K-means: Partitions data into k clusters by minimizing within-cluster variance.
DBSCAN: Density-based clustering that automatically detects clusters and noise points.
The goal is to compare clustering behavior, parameter sensitivity, and suitability for this dataset.
Dataset
Source: sklearn.datasets.load_iris
Features (numeric):
Sepal length (cm)
Sepal width (cm)
Petal length (cm)
Petal width (cm)
Target: Species (Setosa, Versicolor, Virginica) – used only for evaluation, not for clustering


Key Takeaways
K-means is ideal for well-separated, roughly spherical clusters like Iris.
DBSCAN is powerful for irregular-shaped clusters or datasets with noise/outliers.
Choice of algorithm depends on data distribution, cluster density, and goals.
Preprocessing (scaling, encoding) is crucial for both algorithms.


