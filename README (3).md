# K-Means Customer Clustering

## Overview

This project demonstrates the use of the K-Means Clustering algorithm to segment retail store customers based on their purchasing behavior. Customer segmentation is an important business analytics technique that helps companies understand different customer groups and design targeted marketing strategies.

The project uses the Mall Customers dataset and applies unsupervised machine learning to identify distinct customer segments based on annual income and spending score.

---

## Problem Statement

Retail businesses often have large customer bases with varying purchasing patterns. Understanding these patterns can help businesses:

* Improve customer targeting
* Increase customer retention
* Optimize marketing campaigns
* Enhance customer experience
* Maximize revenue opportunities

This project addresses this challenge by grouping customers into meaningful clusters using K-Means Clustering.

---

## Dataset

The dataset contains customer information including:

* Customer ID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1–100)

The clustering process primarily focuses on customer income and spending behavior to identify different customer groups.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Methodology

### 1. Data Preprocessing

* Import dataset
* Inspect data structure
* Check for missing values
* Select relevant features

### 2. Exploratory Data Analysis

* Analyze customer characteristics
* Visualize data distributions
* Understand feature relationships

### 3. Finding the Optimal Number of Clusters

The Elbow Method is used to determine the optimal value of K by analyzing the Within-Cluster Sum of Squares (WCSS).

### 4. K-Means Clustering

The K-Means algorithm is trained on customer data to group similar customers into clusters.

### 5. Visualization

Customer segments are visualized to better understand the characteristics of each cluster.

---

## Results

The model successfully identifies different customer segments such as:

* High Income – High Spending Customers
* High Income – Low Spending Customers
* Average Income – Average Spending Customers
* Low Income – High Spending Customers
* Low Income – Low Spending Customers

These insights can be used by businesses to create more effective marketing strategies and personalized customer experiences.

---

## Key Learnings

Through this project, I gained practical experience in:

* Unsupervised Machine Learning
* K-Means Clustering
* Customer Segmentation
* Data Analysis
* Data Visualization
* Business Intelligence Applications

---

## Future Improvements

Potential enhancements for this project include:

* Hierarchical Clustering
* DBSCAN Clustering
* Customer Recommendation Systems
* Interactive Dashboard Development
* Real-Time Customer Analytics

---

## Installation

```bash
git clone https://github.com/Maganpreet-11/kmeans-customer-clustering.git
cd kmeans-customer-clustering
pip install -r requirements.txt
```

---

## Usage

Run the Jupyter Notebook and execute all cells:

```bash
jupyter notebook
```

Open the notebook and run the project to generate customer clusters and visualizations.

---

## Author

**Maganpreet Singh**

B.Tech Computer Science Engineering Student

Interested in Artificial Intelligence, Machine Learning, Data Science, and Software Development.

---

If you found this project useful, consider giving it a ⭐ on GitHub.
