# Clustering: Implementing-and-Validating-Clustering-Methods-on-Synthetic-and-Real-world-Data

#### Overview
Explore advanced clustering techniques tailored for Machine Learning, Data Mining, Exploratory Data Analysis, and Pattern Recognition. This project focuses on implementing diverse clustering methodologies on both synthetic and real-world datasets, followed by meticulous validation using a combination of internal and external validation techniques.

### Task 1: Clustering on Datasets

**Datasets:** "Dataset 1.csv", "Dataset 2.csv", "Dataset 3.csv", "Dataset 4.csv", "Dataset 5.csv"

**Steps:**

1. **Clustering Methods Application:**
   - Employ K-means and Hierarchical Clustering techniques to generate clusters for each of the five datasets.

2. **Evaluation using External Validation Metrics:**
   - Assess clustering algorithm performance using the following external validation metrics:
     - Adjusted Rand Index (ARI)
     - Normalized Mutual Information (NMI)
     - Fowlkes-Mallows Index (FMI)

3. **Data Visualization:**
   - Visualize data points in 2D or 3D for each dataset:
     - Color them according to the original class.
     - Color them based on the class allocated by each clustering algorithm.


### Task 2: Clustering on World Indicators Dataset
**Dataset:** "WorldIndicators.csv"

**Steps:**

1. **Clustering Method Utilization:**
   - Employ K-means and Hierarchical Clustering to group similar countries based on selected attributes.

2. **Cluster Quality Assessment using Internal Validation Metrics:**
   - Evaluate cluster quality using internal validation metrics:
     - Silhouette Score
     - Calinski-Harabasz Index
     - Davies-Bouldin Index

3. **Identification of Best Clustering Solution:**
   - Identify the optimal clustering solution and provide detailed insights into groups and countries within each cluster.

4. **Generation of Scatter Plots:**
   - Create scatter plots illustrating clustering results with attributes such as "Life expectancy vs GDP" and "Infant Mortality vs GDP," color-coded according to clusters.

Prerequisites:
1. Jupyter Notebooks: Python
2. Required libraries: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, Plotly, scipy

If you have any questions or require assistance, refer to the documentation or reach out to the project contributors.
