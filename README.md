
# My Paw A.I - Dog Breed Finder

**My Paw A.I - Dog Breed Finder** is a machine learning project designed to help users discover their ideal canine companion. The project leverages advanced data analysis techniques and machine learning algorithms to match potential pet owners with dog breeds that suit their lifestyles, preferences, and needs. The accompanying website, built on Wix, serves as an interactive platform to showcase the methodologies, visualizations, and insights derived from the project.

## Project Overview

The goal of this project is to build a robust recommendation system that can predict the best-suited dog breed for a user based on various features including temperament, size, energy levels, grooming needs, and health considerations. The project is structured into several key phases:

- **Data Cleaning & Exploratory Data Analysis (EDA):**  
  Extensive data cleaning is performed to handle missing values, remove duplicates, and standardize the dataset. EDA techniques—using histograms, scatter plots, box plots, and correlation matrices—are applied to understand the distribution of features and relationships among variables.

- **Clustering:**  
  To uncover inherent patterns in the dataset, clustering techniques such as K-Means and Hierarchical Clustering are employed. These algorithms help group similar dog breeds based on attributes like country of origin, fur color, size, and common health issues. Distance metrics (e.g., Euclidean, Manhattan, and cosine similarity) and evaluation metrics like silhouette score guide the determination of the optimal number of clusters.

- **Association Rule Mining (ARM):**  
  Using the Apriori algorithm, the project uncovers hidden associations among different features in the dataset. ARM helps in identifying frequent itemsets and generating rules (if-then statements) that reveal correlations between various breed attributes. Key metrics like support, confidence, and lift are used to evaluate these rules.

- **Principal Component Analysis (PCA):**  
  PCA is applied to reduce the dimensionality of the data, making it easier to visualize and interpret complex relationships among variables. This step aids in identifying the most significant features that influence the clustering and recommendation process.

## Website and User Experience

The website is designed to provide an engaging and informative user experience. Key sections include:

- **Introduction:** An overview of the Dog Breed Finder, explaining the project’s purpose and the value it brings to pet enthusiasts.
- **EDA / Data Cleaning:** Detailed visualizations and descriptions of the data cleaning and exploratory analysis steps, offering insights into the quality and structure of the dataset.
- **Clustering:** An explanation of the clustering methodology along with visual examples, including the silhouette scores and dendrograms used to determine the optimal cluster configuration.
- **Association Rule Mining:** A breakdown of how ARM was used to identify key patterns in the data, complete with visualizations and rule evaluations.
- **PCA:** A description of how PCA helped in dimensionality reduction and feature extraction, facilitating a clearer understanding of the data’s underlying structure.
- **Conclusion:** A summary of the insights gained from the machine learning analyses, including how these findings can guide potential dog owners in making informed decisions.

## Technologies Used

- **Machine Learning & Data Analysis:** Python, R, scikit-learn, pandas, NumPy, and Matplotlib/Seaborn for visualization.
- **Clustering & ARM Algorithms:** K-Means, Hierarchical Clustering, and the Apriori algorithm.
- **Dimensionality Reduction:** Principal Component Analysis (PCA).
- **Website:** Wix for design and content presentation.


---
