# eCommerce Transactions Dataset

## Overview

This repository contains a dataset of eCommerce transactions, providing detailed insights into customer behavior, product performance, and sales trends. The dataset is designed to facilitate exploratory data analysis (EDA), predictive modeling, and other data science applications.

## Dataset Description

The dataset includes the following files:

- `Customers.csv`: Contains customer profiles, including attributes such as customer ID, name, region, and signup date.
- `Products.csv`: Details of products, including product ID, name, category, and price.
- `Transactions.csv`: Logs of customer transactions, including transaction ID, customer ID, product ID, transaction date, quantity, and total value.

## Objectives

The primary objectives of this project are:

- **Exploratory Data Analysis (EDA):** Analyze customer distribution, product categories, and transaction trends to derive actionable business insights.
- **Customer Segmentation:** Implement clustering techniques to segment customers based on their profiles and transaction history.
- **Lookalike Modeling:** Develop a model to recommend similar customers based on profile and transaction data.

## Repository Structure

The repository contains the following files and directories:

- `README.md`: This file.
- `Customers.csv`: Customer data.
- `Products.csv`: Product data.
- `Transactions.csv`: Transaction data.
- `filename_EDA.ipynb`: Jupyter notebook for exploratory data analysis.
- `filename_Clustering.ipynb`: Jupyter notebook for clustering analysis.
- `filename_Lookalike.ipynb`: Jupyter notebook for lookalike modeling.
- `Clustering_Results.csv`: Results from the clustering analysis.
- `filename_Lookalike.csv`: Results from the lookalike analysis.

## Getting Started

To begin working with this dataset:

1. **Clone the Repository:**

git clone https://github.com/Manasa2003k/eCommerce-Transactions-Dataset.git

2. **Navigate to the Directory:**

cd eCommerce-Transactions-Dataset

3. **Install Dependencies:**

Ensure you have Python 3.x installed. Then, install the required libraries:

pip install -r requirements.txt

4.**Run Jupyter Notebooks:**

Start Jupyter Notebook and open the desired notebook to begin analysis:

jupyter notebook


5. **Requirements:**

The project requires the following Python libraries:
pandas
numpy
matplotlib
seaborn
scikit-learn

These can be installed using pip:

pip install pandas numpy matplotlib seaborn scikit-learn

6. **License:**
   
This project is licensed under the MIT License - see the LICENSE file for details.
