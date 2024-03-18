# Clustering: Implementing-and-Validating-Clustering-Methods-on-Synthetic-and-Real-world-Data

### Clustering Toolkit: Unveiling Insights from Data

#### Overview
Explore advanced clustering techniques tailored for Machine Learning, Data Mining, Exploratory Data Analysis, and Pattern Recognition. This project focuses on implementing diverse clustering methodologies on both synthetic and real-world datasets, followed by meticulous validation using a combination of internal and external validation techniques.

#### Clustering Methods
- **K-means**: Partition datasets into clusters based on similarity.
  - Implementation: `KMeans(n_clusters=k, random_state=seed)`
- **Hierarchical Clustering**: Construct tree-like structures of clusters using Agglomerative Hierarchical Clustering.
  - Implementation: `AgglomerativeClustering(n_clusters=k)`

#### Task 1: Clustering on Datasets
**Datasets:** "Data1.csv", "Data2.csv", "Data3.csv", "Data4.csv", "Data5.csv"

**Steps:**
1. Apply K-means and hierarchical clustering to generate clusters for each dataset.
2. Evaluate clustering algorithms using external validation metrics:
  - Adjusted Rand Index (ARI)
  - Normalized Mutual Information (NMI)
  - Fowlkes-Mallows Index (FMI)
3. Visualize data points in 2D or 3D, coloring them based on original class and clusters.

#### Task 2: Clustering on World Indicators Dataset
**Dataset:** "WorldIndicators.csv"

**Steps:**
1. Utilize K-means and hierarchical clustering to group similar countries based on selected attributes.
2. Assess cluster quality using internal validation metrics:
  - Silhouette Score
  - Calinski-Harabasz Index
  - Davies-Bouldin Index
3. Identify the best clustering solution and detail groups and countries within each group.
4. Generate scatter plots depicting clustering results with attributes such as "Life expectancy vs GDP" and "Infant Mortality vs GDP," colored according to clusters.

#### Usage
1. **Dataset Preparation:** Download and load provided datasets.
2. **Task 1 Execution:** Execute K-means and hierarchical clustering on synthetic datasets. Evaluate performance with external validation metrics and visualize results.
3. **Task 2 Execution:** Apply clustering on the World Indicators dataset. Assess cluster quality, report the best solution, and generate scatter plots.
   
#### Dependencies
- **Python**
- **Jupyter Notebooks**
- **Required libraries:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, Plotly, scipy
   
Feel free to explore code files for detailed implementation and results. For queries or assistance, consult documentation or contact project contributors.
