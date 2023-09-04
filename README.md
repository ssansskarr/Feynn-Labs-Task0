# Feynn Labs Task 2 Repository

This repository contains Python code for data analysis, dimensionality reduction, clustering, and visualization of the McDonald's dataset. The project is part of the task assigned by Feynn Labs.

## Dataset
The dataset used in this project is the McDonald's dataset, which includes various attributes related to McDonald's food items. The dataset is publicly available and can be accessed [here](https://homepage.boku.ac.at/leisch/MSA/datasets/mcdonalds.csv).

## Code Description

### 1. Data Preprocessing
- In the Jupyter Notebook `code_convert.ipynb`, the dataset is loaded and preprocessed.
- The first 11 columns of the dataset are selected, and "Yes" values are converted to 1, and everything else is converted to 0 for further analysis.

### 2. Principal Component Analysis (PCA)
- Principal Component Analysis (PCA) is performed using scikit-learn.
- The code calculates eigenvalues, proportion of variance explained by each component, and cumulative variance explained.
- The results are displayed and can be used for dimensionality reduction.

### 3. K-Means Clustering
- K-Means clustering is applied to the preprocessed data with a range of cluster numbers (2 to 8).
- The silhouette score is calculated for each cluster number to determine the optimal number of clusters.
- A plot of the silhouette scores is generated to aid in cluster number selection.
- The code also includes optional cluster relabeling.

### 4. Visualization
- The Jupyter Notebook includes multiple visualization plots, including scatter plots, silhouette score plots, and adjusted Rand index plots.
- These visualizations help in understanding the data and evaluating clustering performance.

## Author
- Sanskar Gupta (https://github.com/ssansskarr)



Happy exploring and coding!
