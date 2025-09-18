 Clustering and Dimensionality Reduction Project
##  Dataset
- Source: Google Colab (uploaded via Drive)  
- The dataset contains multiple features describing observations for analysis.  
- Preprocessing steps included handling missing values, scaling features using StandardScaler, and preparing the data for clustering.  

## Methods used
1. Preprocessing
   - StandardScaler for normalization  
   - Handling missing values  

2. Dimensionality Reduction
   - PCA (Principal Component Analysis) to reduce high-dimensional data  
   - t-SNE for 2D visualization of clusters  

3. Clustering  
   - KMeans clustering (tested with different 'n_clusters')  
   - Hierarchical Clustering (linkage, dendrograms, flat clusters with 'fcluster')  

4. Evaluation
   - Silhouette Score to measure cluster quality  
   - Adjusted Rand Score for comparison with ground truth (if available)  

##  Results
- PCA reduced the dataset to key components while preserving most variance.  
- t-SNE provided a clear 2D visualization, showing potential natural clusters.  
- KMeans produced clusters with good silhouette scores.  
- Hierarchical Clustering dendrogram suggested a suitable cluster number.  
- Overall, clustering methods revealed patterns that would not be obvious in the raw dataset.  

