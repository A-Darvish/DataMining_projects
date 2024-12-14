# Data Mining Practice 3

This project integrates all the concepts from previous practices to create an end-to-end data mining pipeline. It covers everything from data preprocessing to model building and optimization.

## Overview
This project implements a complete data mining workflow, including:
- Data cleaning, transformation, and feature engineering.
- Building and optimizing machine learning models.
- Preparing the pipeline for deployment-ready insights.

## Key Features
- **Clustering Techniques**:
  - K-Means Clustering (optimal `k` determined using the Elbow method).
  - DBSCAN for density-based clustering.
- **Association Rules**:
  - Apriori Algorithm for mining frequent itemsets and discovering rules in transactional datasets.
- **Evaluation Metrics**:
  - Silhouette Score for clustering validation.
  - Support, Confidence, and Lift for association rules.

## Datasets
1. `Country-data.csv`: Includes country-level statistics.
2. `Grocery-store.csv`: Contains transactional data for association rule mining.


## Prerequisites
- Python 3.7+
- Required libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - jupyter

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/A-Darvish/DataMining_Projects.git
   ```
2. Navigate to the directory:
   ```bash
   cd DM_P3
   ```

## Usage
1. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Execute the cells in `DM_P3.ipynb` sequentially.

## Results
- **Clustering**:
  - K-Means with `k=4` and PCA provided compact clusters.
  - DBSCAN captured density-based clusters but required parameter tuning.
- **Association Rules**:
  - Top 3 frequent itemsets were identified with strong support and confidence values.
  - Rules such as "If Milk and Bread, then Biscuit" were extracted for decision-making.


## Insights
The project highlights the power of unsupervised learning techniques for exploratory data analysis. Clustering methods and association rules are particularly useful for understanding patterns in large datasets.
