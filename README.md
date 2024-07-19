# Customer Segmentation Using K-means Clustering

## Overview
This project aims to segment customers into distinct groups using the K-means clustering algorithm. By analyzing customer data, we can identify patterns and behaviors that can help businesses tailor their marketing strategies, improve customer satisfaction, and enhance revenue.

## Project Structure

### Importing Libraries
Essential libraries for data manipulation, visualization, and clustering are imported.

### Loading and Inspecting the Data
The dataset is loaded and inspected to understand its structure and content.

### Data Cleaning
The data is cleaned to handle missing values, duplicates, and other inconsistencies.

### Exploratory Data Analysis
Various visualizations and statistical analyses are performed to explore the data and gain insights.

### K-Means Clustering
Clustering is performed on different feature combinations to identify distinct customer segments.
- **Clustering on Age and Spending Score**: Understands the relationship between customer age and spending behavior.
- **Clustering on Annual Income and Spending Score**: Segments customers based on income levels and spending patterns.
- **Clustering on Age, Annual Income, and Spending Score**: Provides a comprehensive clustering by considering age, income, and spending behavior simultaneously.

### Building the K-Means Model and Visualizing the Clusters
The K-means model is built and clusters are visualized for each feature combination.
- **Elbow Method**: Used to determine the optimal number of clusters for each feature combination.
- **Cluster Visualization**: Visualizations help in understanding the distinct characteristics of each cluster.

### Evaluation
The silhouette score is calculated to evaluate the clustering performance.

## Conclusion
- **Effective Clustering**: The K-means algorithm successfully segmented customers into distinct groups based on their behaviors and attributes.
- **Silhouette Score**: Achieved a silhouette score of 0.377, indicating reasonably well-formed clusters.
- **Cluster Visualization**: Provided clear insights into the distinct characteristics of each cluster.
- **Evaluation Metrics**: The silhouette score suggests meaningful clustering with room for improvement.

## What I Have Learned and Gained

### Technical Skills
- **Data Preprocessing**: Gained experience in cleaning and preparing data for analysis, including handling missing values and outliers.
- **Exploratory Data Analysis (EDA)**: Learned to use various statistical and visualization techniques to understand the data and extract meaningful insights.
- **K-means Clustering**: Developed a solid understanding of the K-means clustering algorithm, including how to implement it, determine the optimal number of clusters using the Elbow Method, and interpret the results.
- **Model Evaluation**: Learned to evaluate clustering performance using the silhouette score, which helps in assessing the quality of the clusters formed.
- **Data Visualization**: Enhanced skills in visualizing data and clustering results using libraries like matplotlib and seaborn to create clear and informative plots.

### Analytical Skills
- **Pattern Recognition**: Improved ability to recognize patterns and relationships within the data, leading to better segmentation of customers.
- **Insights Generation**: Learned to generate actionable insights from data analysis that can inform business decisions and strategies.

### Practical Application
- **Customer Segmentation**: Gained practical experience in segmenting customers based on various features like age, annual income, and spending score, which is crucial for targeted marketing and personalized customer experiences.
- **Business Impact**: Understood the importance of customer segmentation in improving marketing strategies, customer satisfaction, and overall business revenue.


