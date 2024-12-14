# Data Mining Practice 2

This project focuses on applying machine learning algorithms to real-world datasets. It provides hands-on experience with classification and clustering techniques, model evaluation, and performance optimization.

## Overview
This project demonstrates:
- Implementation of machine learning algorithms (classification and clustering).
- Evaluation of model performance using metrics like accuracy and F1-score.
- Visualization of results for better interpretation.

## Key Features
- Supervised learning: Classification models.
- Unsupervised learning: Clustering techniques.
- **Algorithms Used**:
  - Support Vector Machines (SVM)
  - Bayesian Networks
  - K-Nearest Neighbors (KNN)
  - Random Forest
- **Hyperparameter Tuning**: GridSearchCV for systematic hyperparameter optimization.
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score.

## Dataset
- The dataset is preprocessed and split into training and testing sets.
- Features include categorical and numerical attributes, one-hot encoded for model compatibility.


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
   cd DM_P2
   ```

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Execute the cells in `DM_P2.ipynb` sequentially.

## Results
- SVM achieved the highest precision and recall with tuned hyperparameters.
- KNN with an optimized number of neighbors provided competitive accuracy.
- Random Forest showed robust performance, especially in handling complex datasets.


## Insights
This project demonstrates the importance of hyperparameter tuning and model selection for different types of data. It serves as a guide for choosing the best algorithms based on project requirements.
