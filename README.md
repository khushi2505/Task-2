# Task 2 K-Means Clustering for Customer Segmentation

## Project Overview
This project is part of my Data Science internship at Prodigy InfoTech. The objective is to develop a K-means clustering algorithm to group customers of a retail store based on their purchase history. This segmentation can help identify distinct customer groups, allowing the business to implement more targeted marketing strategies.

## Dataset Used
The dataset used for this project is sourced from Kaggle
- [Customer Segmentation Dataset](httpswww.kaggle.comdatasetsvjchoudhary7customer-segmentation-tutorial-in-python)

It contains various customer attributes such as their spending patterns, age, income, and more, which will be used to create customer clusters.

## Project Structure
- customer_segmentation.py The main Python script that contains the implementation of the K-means clustering algorithm.
- cleaned_data.csv Cleaned and pre-processed version of the dataset after handling missing values and feature scaling.
- clustered_customers.csv The resulting dataset containing the assigned clusters for each customer.

## Key Steps

### 1. Data Preprocessing
- Handling Missing Values
  - Any missing values were addressed by filling or removing based on the importance of the feature.
  
- Feature Scaling
  - Numerical features like income and spending were standardized to ensure they have equal weight in the clustering process.
  
### 2. Feature Selection
- Selected features related to customers' purchasing behavior, including spending scores, annual income, and other relevant attributes.

### 3. K-Means Clustering
- Elbow Method
  - Used to determine the optimal number of clusters by plotting the Within-Cluster-Sum-of-Squares (WCSS) against the number of clusters.
  
- K-Means Algorithm
  - Implemented K-means clustering to segment customers into groups based on their purchasing behavior.

### 4. Cluster Analysis
- Cluster Visualization
  - Created 2D scatter plots to visualize customer segments, highlighting similarities and differences between groups.
  
- Cluster Characteristics
  - Analyzed the customer segments to understand key features of each cluster (e.g., high spenders, budget-conscious customers, etc.).

## Results
The K-means clustering algorithm successfully grouped customers into distinct clusters based on their purchasing history. These customer segments can now be used for further business insights, personalized marketing, or customer service enhancements.

## Conclusion
This project demonstrates the effectiveness of K-means clustering for customer segmentation. By identifying distinct customer groups, businesses can create more targeted and efficient marketing strategies, improving overall customer satisfaction and sales.
