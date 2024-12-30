# Clustering-Portfolios
The step how to clustering a case with K-Means and Hierarchical
**K-MEANS CLUSTERING**
Imports:
  KMeans for clustering.
  pandas for data manipulation.
  MinMaxScaler for data normalization.
  matplotlib.pyplot for visualization.
Dataset:
  Loads an Excel file named Form Andat Clustering_ Sepatu (Responses).xlsx.
Preview:
  Displays the dataset's first few rows.
Select Features:
  Subset the dataset to relevant features (tinggi_badan and ukuran_sepatu).
Visualize Data:
  Create a scatter plot to visualize relationships between features.
Fit K-Means Model:
  Instantiate the KMeans model with a specified number of clusters (e.g., 3). Fit the model and predict cluster labels.
Assign Clusters:
  Add the predicted cluster labels to the dataset as a new column.
Visualize Clusters:
  Separate data points by clusters and visualize them with different colors.

  **HIERARCHICAL CLUSTERING**
  Imports:
    Libraries like pandas, numpy, and clustering-related modules (linkage, dendrogram) from scipy.
    Metrics like silhouette_score for evaluating clusters.
    Visualization tools like matplotlib and seaborn.
Dataset:
  Loads a CSV file named hierarchical dataset responsi.csv.
Preview:
  Displays the dataset's first few rows.
Visualize Data:
  Use scatter plots to explore feature distributions.
Linkage Matrix:
  Compute linkage matrices using different methods (single, complete, average, ward). Visualize dendrograms for each linkage method.
Evaluate Dendrograms:
  Evaluate cophenetic correlation to assess the quality of the hierarchical clustering.
Final Dendrogram:
  Use the ward linkage method for detailed visualization and analysis.
Cluster Assignment:
  Assign clusters by cutting the dendrogram at a specific distance (e.g., cut_height=13).

**INSIGHT**:
K-Means is suitable for datasets with clear spherical clusters and a predefined number of clusters.
Hierarchical clustering is better for exploring hierarchical relationships or when the number of clusters is not pre-specified.
