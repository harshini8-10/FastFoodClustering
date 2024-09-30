# Title of the Project : Clustering Analysis of Fast Food Nutrition Dataset 
# Description : 
This project involves the application of clustering techniques on the Fast Food Nutrition dataset to identify patterns based on nutritional factors such as calories, total fat, and trans fat. Various data embedding methods (PCA, UMAP, MDS, IsoMAP, Spectral Embedding, t-SNE) were explored to reduce the data's dimensionality, followed by clustering algorithms (K-Means, DBSCAN, Agglomerative Clustering) to find meaningful clusters. The project also involves visualization and analysis of cluster memberships to extract insights.
# Goals :
•	 Data Preprocessing: Handle missing data, scale numeric variables, and apply power transformations.

•	Data Embeddings: Use PCA, UMAP, MDS, IsoMAP, Spectral Embedding, and t-SNE to visualize the data in lower dimensions.

•	 Clustering: Apply K-Means, DBSCAN, and Agglomerative Clustering to the embedded data.

•	        Cluster Analysis: Evaluate clustering solutions and analyze cluster memberships to determine the best model.

# Technologies Used :
## Python Libraries 
•  Pandas: Data manipulation

•  Scikit-learn: Clustering and embeddings

•  Seaborn, Matplotlib: Visualization

•  UMAP, TSNE: Advanced embeddings

## Clustering Models:
o	K-Means

o	DBSCAN


o	Agglomerative Clustering

## Embedding Techniques: 
o	PCA

o	UMAP 


o	MDS 

o	IsoMAP 


o	Spectral Embedding 

o	t-SNE

# Challenges and Future Work :
•	Challenges: Handling high-dimensional data, selecting optimal clustering algorithms for non-linear data, and evaluating cluster quality.

•	Future Work: Explore additional clustering techniques (e.g., Gaussian Mixture Models), tune hyperparameters for DBSCAN, and apply clustering to a broader range of datasets for validation.

# Table of Contents :
1.	Introduction
2.	Project Objectives
3.	Project Scope
4.	Methodology
5.	How to Install and Run the Project
6.	How to Use the Project
7.	Clustering Process and Analysis
8.	Results
9.	Conclusion

# 1.	Introduction
The goal of this project is to explore clustering models on the FastFood dataset. The dataset includes nutritional values such as total fat, trans fat, and calories. Clustering models were used to group food items based on these characteristics, providing insights into nutritional patterns among fast food offerings.

# 2.	Project Objectives
•  Apply dimensionality reduction techniques to visualize the data.

•  Use clustering algorithms to categorize food items into meaningful groups.

•  Analyze the resulting clusters and identify relationships among different fast food items.

# 3.	Project Scope

•  Dataset: fastfood.csv dataset (CSV file).
•  Clustering Methods: K-Means, DBSCAN, Agglomerative Clustering.

•  Embedding Methods: PCA, UMAP, MDS, IsoMAP, Spectral Embedding, t-SNE.

•  Tools: Python, Jupyter Notebook
# 4.	Methodology
## Data Preprocessing:
•	Handle missing values with imputation.

•	Scale numeric features using RobustScaler and StandardScaler.

•	Apply PowerTransformer for normalization.


## Dimensionality Reduction:
•	Use PCA and UMAP to explore linear and non-linear structures in the data.
## Clustering:
•	Evaluate K-Means, DBSCAN, and Agglomerative Clustering models.

•	Compare clustering performance using silhouette scores and cluster visualization.
# 5.	How to Install and Run the Project
•	Clone the Repository:
git clone https://github.com/harshini8-10/FastFoodClustering.git
# 6.	How to Use the Project:
•  The Jupyter notebook guides you through data exploration, preprocessing/ feature engineering techniques, and model training.

•  Follow along with the embedded code to understand the clustering techniques used.
# 7. Clustering Process and Analysis:
The clustering process involved:

•	Data Preprocessing – Including scaling and imputation.

•	Dimensionality Reduction – Visualizing the data using various embedding techniques.

•	Clustering – Building models with K-Means, DBSCAN, and Agglomerative Clustering.

•	Cluster Evaluation – Using silhouette scores and visualization to compare cluster quality.
# 8. Results:
•	Best Embedding – UMAP provided the clearest separation of clusters in a non-linear structure.

•	Dimensionality Reduction – DBSCAN was chosen due to its ability to detect outliers and form well-defined clusters.

# 9. Conclusion:
This project demonstrated the effective use of clustering models on a nutritional dataset. DBSCAN was the most suitable clustering method for this task, identifying distinct groups of food items based on their nutritional content.
