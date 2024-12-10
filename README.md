# Customer Segmentation: Mall Customers

This repository contains a machine learning project for customer segmentation using clustering techniques. The project uses the **Mall Customers** dataset to group customers based on their annual income and spending score, helping the mall owner identify profitable customer segments.

## 📊 Project Overview

The **Customer Segmentation** project aims to segment mall customers into groups based on their income and spending score. The dataset contains information such as:

- **Customer ID**
- **Gender**
- **Age**
- **Annual Income**
- **Spending Score**

The goal is to identify the most profitable customer groups using clustering techniques, which can help in targeting the right audience for marketing strategies.

## 🛠 Features

- **Data Preprocessing**: 
   - **Label Encoding** for categorical data like Gender.
   - **Scaling** or **Normalization** for features like Annual Income and Spending Score.
   
- **Clustering Algorithms Applied**:
   1. **K-Means Clustering**: To group customers based on similarity.
   2. **Hierarchical Clustering**: To visualize and segment customers using dendrograms.
   
- **Data Preparation**: 
   - Splitting the dataset into training and testing sets, if needed.
   
- **Model Evaluation**:
   - Use **Silhouette Score**, **Dunn Index**, or **Elbow Method** to evaluate clustering performance.

- **Cross-Validation**: 
   - Apply cross-validation to ensure the robustness of the segmentation.

## 📁 File Structure

- **`Customer_Segmentation.ipynb`**: The Jupyter notebook containing the complete machine learning workflow, from data preprocessing to model evaluation.
- **`mall_customers.csv`**: The dataset file containing the customer data.

## 🛑 Prerequisites

Ensure you have the following libraries installed:

- **Python 3.x**
- **pandas**: For data manipulation.
- **numpy**: For numerical operations.
- **matplotlib**: For plotting.
- **seaborn**: For advanced data visualization.
- **scikit-learn**: For machine learning algorithms.
- **scipy**: For hierarchical clustering.

Install the dependencies by running:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

## 🚀 Steps

1. **Data Preprocessing**: Clean the data by handling missing values and encoding categorical variables. Apply scaling or normalization to numeric features for clustering.

2. **Clustering Algorithm Application**:
   - **K-Means Clustering**: Apply K-Means to segment customers into clusters based on spending score and income.
   - **Hierarchical Clustering**: Use hierarchical clustering to visualize customer segmentation and determine the optimal number of clusters using a dendrogram.

3. **Model Evaluation**: 
   - Evaluate the models using metrics like **Silhouette Score** to measure the quality of clustering.
   - Visualize the clusters using scatter plots or pair plots to get insights into customer segments.

4. **Cross-Validation**: 
   - Implement cross-validation techniques (where applicable) to ensure the reliability of the clustering results.

## 📜 License

This project is licensed under the [MIT License](LICENSE).
