
# Customer Clustering
![image alt](https://github.com/SyedAliNice/Customer-Clustering-based-on-Credit-card-usage-Project/blob/427978b7c559315287de7c8c3657d16386451aca/a-digital-infographic-for-a-business-ana_yi2wUKw-SKKNb6RHkNBjlg_R2UrBEj2S2274Jjd41J7bA-fotor-20250327151312.jpg)
# Project Overview

This project focuses on deriving customer insights based on their credit card usage features. It involves data preprocessing, clustering, and dimensionality reduction techniques to segment customers and understand their behavior patterns.
# Files and Directories
1.  Customer_Clustering.ipynb: Jupyter Notebook containing the main implementation of the clustering process.
2.  Customer_Clustering_colab.ipynb: Google Colab-compatible version of the clustering notebook.
3.  Customer_Clustering_final.ipynb: Final version of the clustering implementation with refined analysis.
4.  Customer-Data - 2.csv: Dataset used for training and evaluation.
# Data Source
The dataset used can be found here: Kaggle Customer Data Clustering
# Objective
The main objective of this project is to segment customers based on their credit card usage patterns using clustering techniques.
# Implementation Steps
  # Data Preprocessing
1.  Visualizing and transforming data (log, power, exponential transformations if needed).
2.  Removing highly correlated or irrelevant features.
3.  Encoding categorical variables as required.

#   Clustering Techniques
1.  Training K-Means and determining the optimal number of  clusters.    
2.  Using DBSCAN and tuning parameters to find optimal cluster formation.
3.  Visualizing clusters using t-SNE embedding
4.  Assigning meaningful cluster names such as "Reckless Spenders."
# Principal Component Analysis (PCA)    
1.  Normalizing variables and applying PCA.
2.  Plotting variance explained vs. PCA dimensions.
3.  Reconstructing data using different PCA dimensions and computing MSE.
# Installation
1.  Clone this repository.
2.  Install dependencies using:
    pip install -r requirements.txt
3.  Ensure the dataset (Customer-Data - 2.csv) is in the correct directory.
#   Dependencies
1.  Python 3.x
2.  Scikit-learn
3.  Pandas
4.  NumPy
5.  Matplotlib
6.  Seaborn
7.  Jupyter Notebook


