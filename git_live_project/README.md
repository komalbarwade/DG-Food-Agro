# DG-Food-Agro
Overview:
New DG Food Agro, with a rich history of 130 years, specializes in exporting wheat from India to various countries. This project aims to analyze 18 years of export data, applying unsupervised learning techniques to cluster countries based on sales. The objective is to identify patterns, group similar countries, and provide insights into export performance.

Objectives:

Data Preprocessing:

Check for missing values in the dataset.
Update headers to "country" and "year."
Cleanse the data by handling null or blank values.

Exploratory Data Analysis (EDA):

Conduct EDA to understand the distribution and characteristics of the export data.
Identify trends, outliers, or patterns that may influence clustering.

Scaling Data:

Standardize exports across years to bring them to the same scale.
Ensure data is ready for clustering analysis.

Principal Component Analysis (PCA):

Apply PCA to reduce dimensionality and capture maximum variance.
Determine the number of principal components needed for analysis.

Cluster Analysis:

Plot elbow chart or scree plot to determine the optimal number of clusters.
Apply K-means and Hierarchical clustering algorithms.
Evaluate and showcase clustering results.

Interpretation and Insights:

Explore grouping countries based on both years and principal components.
Identify consistent performers and countries with export potential.
Analyze scale and position of clusters to pinpoint largest importers.

Implementation Steps:
Read and preprocess the data.
Perform EDA for data exploration.
Scale the data for uniformity.
Apply PCA for dimensionality reduction.
Conduct cluster analysis using K-means and Hierarchical clustering.
Evaluate results and interpret insights.

Note:
The project is designed to be repeatable for future data additions.
Results are presented visually through charts and interpretations for easy understanding.
