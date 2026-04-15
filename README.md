# people-analytics-case-06-Employees-Clustering

## Overview

This project focuses on applying **unsupervised machine learning techniques** to segment employees into meaningful groups based on their characteristics.

Using a simulated HR dataset (~600 employees), the goal is to uncover hidden patterns that can support **data-driven HR decision-making**.

---

## Objectives

- Identify natural groupings of employees
- Understand workforce segmentation
- Support HR strategies such as:
  - Talent management
  - Retention plans
  - Compensation strategies
  - Employee development

---

## Dataset

The dataset includes typical HR variables such as:

- Demographics (age, tenure, etc.)
- Performance metrics
- Engagement indicators
- Compensation-related features

Data source:  https://raw.githubusercontent.com/Pablolg87/people-analytics-case-06-Employees-Clustering/refs/heads/main/employee_clustering_dataset.csv

---

## Project Workflow

### 1. Data Loading
Dataset is imported directly from GitHub using pandas.

### 2. Data Cleaning
- Removal of duplicates  
- Handling missing values  
- Correction of inconsistencies  

### 3. Exploratory Data Analysis (EDA)
- Distribution analysis  
- Correlation analysis  
- Outlier detection  

### 4. Feature Preparation
- Scaling and normalization  
- Feature selection  

### 5. Clustering Model
- Algorithm: **K-Means**
- Optimal number of clusters determined using:
  - Elbow Method

### 6. Cluster Interpretation
- Profiling each employee segment  
- Identifying business insights  

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Key Insights

The clustering approach enables:

- Identification of distinct employee segments
- Better understanding of workforce composition
- More targeted HR interventions

---

## How to Run

```python
import pandas as pd

url = "https://raw.githubusercontent.com/Pablolg87/people-analytics-case-06-Employees-Clustering/refs/heads/main/employee_clustering_dataset.csv"
df = pd.read_csv(url)
