# Customer-Segmentation-using-K-Means-Clustering

## Project Overview

This project implements a customer segmentation model using K-Means clustering in Python. The goal is to analyze and categorize customer data from a retail dataset based on their annual income and spending score.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Steps Involved](#steps-involved)
- [Results](#results)
- [Visualizations](#visualizations)
- [How to Run the Project](#how-to-run-the-project)
- [License](#license)

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset

The dataset used in this project is the **Mall_Customers.csv** file, which contains information about 200 customers, including the following features:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Steps Involved

1. **Importing Dependencies**: Load necessary libraries for data manipulation and visualization.
   
2. **Data Collection & Analysis**:
   - Load the dataset into a Pandas DataFrame.
   - Analyze the dataset to understand its structure and check for missing values.

3. **Feature Selection**: Choose relevant features for clustering (Annual Income and Spending Score).

4. **K-Means Clustering**:
   - Determine the optimal number of clusters using the Elbow method.
   - Train the K-Means model with the identified number of clusters.

5. **Results**: Obtain cluster labels for each customer.

6. **Visualizations**: Plot the clusters and their centroids to visualize customer segments.

## Results

The K-Means clustering model identified **5 distinct customer segments** based on their annual income and spending behavior.

## Visualizations

The following visualizations illustrate the customer groups:

- Elbow method graph to determine the optimal number of clusters.
- Scatter plot showing customer segments and their centroids.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Customer-Segmentation-KMeans.git
