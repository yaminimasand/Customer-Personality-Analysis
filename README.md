# Customer-Personality-Analysis

## Overview
This project uses **unsupervised machine learning** techniques to segment customers based on demographic and behavioral data. By applying clustering algorithms such as **K-Means** and **Hierarchical Clustering**, the model identifies distinct customer groups. These segments can be used to design **targeted marketing strategies** and improve customer engagement.

### Project Objectives:
- Perform **customer segmentation** using clustering algorithms.
- Visualize customer behavior using data-driven insights.
- Provide actionable recommendations for **personalized marketing** strategies.

## Features
- **Data Preprocessing**: Handle missing data, normalization, and outlier detection.
- **Clustering Algorithms**:
  - K-Means Clustering
  - Hierarchical Clustering (Agglomerative)
  - RFM (Recency, Frequency, Monetary) Analysis
- **Visualization**: 
  - Cluster distributions and feature importance using **PCA** and **t-SNE**.
  - **Heatmaps** for correlation analysis within clusters.
  - Demographic distributions and market segment visualizations.
- **Marketing Insights**: Provide recommendations for tailored marketing strategies for each customer segment.

## Tools and Libraries
- **Python Libraries**:
  - Pandas (Data manipulation)
  - NumPy (Numerical operations)
  - Scikit-learn (Machine learning and clustering)
  - Matplotlib & Seaborn (Data visualization)
  - Plotly (Interactive plots)
  - Scipy (Hierarchical clustering)
- **Jupyter Notebook**: Interactive development environment for executing and visualizing results.

## Dataset
The project uses a customer dataset that contains demographic and transactional information. Example features include:
- Customer Age
- Gender
- Annual Income
- Spending Score
- Frequency of Purchases
- Product Categories Purchased

Dataset sources can include [Kaggle's Customer Segmentation Data](https://www.kaggle.com/imakash3011/customer-personality-analysis) or any relevant customer-related dataset.

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yaminimasand/Customer-Personality-Analysis.git
2. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
