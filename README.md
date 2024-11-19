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

## Visualizations and Insights

### 1. **Cluster Plots**
   - **Purpose**: Visualize customer segmentation after applying clustering algorithms like K-Means, using dimensionality reduction techniques such as **PCA** (Principal Component Analysis) or **t-SNE** (t-Distributed Stochastic Neighbor Embedding).
   - **Insight**: By reducing the dimensionality of the data, we can visualize how well the clusters are separated, giving a clearer picture of distinct customer segments.

### 2. **Elbow Method**
   - **Purpose**: Identify the optimal number of clusters for K-Means clustering using the **Elbow Method**.
   - **Insight**: The Elbow Method helps determine the number of clusters at which the within-cluster sum of squares (WCSS) begins to plateau, indicating the most efficient number of clusters.

### 3. **RFM Analysis**
   - **Purpose**: Segment customers based on **Recency**, **Frequency**, and **Monetary** values for targeted marketing.
   - **Insight**: By categorizing customers into different segments based on their purchase behavior, marketing strategies can be tailored for each group, enhancing customer retention and engagement.

### 4. **Demographic Insights**
   - **Purpose**: Identify key demographic characteristics (e.g., age, gender, income) of each customer segment to aid in marketing strategy.
   - **Insight**: Understanding the demographic makeup of each cluster helps in designing more targeted and personalized marketing campaigns that resonate with each group.

## Conclusion
This project enables businesses to better understand their customer base, providing valuable insights into customer behavior. The segmented clusters allow for more personalized marketing, leading to higher customer satisfaction and increased revenue.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
