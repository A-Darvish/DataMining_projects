# Data Mining Practice 1

This project is divided into two parts that focus on foundational and advanced data mining techniques. These notebooks aim to introduce and build upon essential data preprocessing, exploratory data analysis, and feature engineering techniques.

## Part 1: Data Mining Practice 1.1
**Overview**:  
This part introduces basic data mining workflows, focusing on:
- Data preprocessing, including handling missing values and outliers.
- Exploratory Data Analysis (EDA) with visualizations.

**Key Features**:
- Data cleaning and transformation.
- Summary statistics and visual exploration of datasets.

## Part 2: Data Mining Practice 1.2
**Overview**:  
This part delves into advanced data mining topics, including:
- Feature engineering for better model performance.
- Data transformation techniques to improve compatibility with algorithms.
- **Regression Models**: Linear and Polynomial regression for population prediction.
- **Classification Models**: Decision Tree, Random Forest, KNN, SVM (Linear and Non-linear).
- **Evaluation Metrics**: Mean Squared Error (MSE), Accuracy, Precision, Recall.

## Dataset
- Source: `worldcities.xlsx`.
- Features: City names, population, and additional demographic attributes.

**Key Features**:
- Advanced visualizations for insights.
- Techniques to prepare datasets for machine learning.

## Prerequisites
- Python 3.7+
- Required libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - jupyter

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/A-Darvish/DataMining_Projects.git
   ```
2. Navigate to the directory for Part 1 or Part 2:
   ```bash
   cd DM_P1_part1  # For Practice 1.1
   cd DM_P1_part2  # For Practice 1.2
   ```

## Usage
1. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open and execute the cells in:
   - `DM_P1_part1.ipynb` for Practice 1.1.
   - `DM_P1_part2.ipynb` for Practice 1.2.
   
## Results
- Polynomial regression achieved better accuracy for higher-degree relationships.
- Non-linear SVM outperformed other classifiers for population level prediction.
