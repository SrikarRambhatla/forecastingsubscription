# forecastingsubscription

# Bank Marketing Data Analysis and Classification

## Overview
This Jupyter Notebook, `Final_Project.ipynb`, is a part of a comprehensive project that focuses on analyzing the Bank Marketing dataset and building classification models to predict whether a client will subscribe to a term deposit. The project encompasses various stages such as data preprocessing, exploratory data analysis, feature engineering, and the implementation and evaluation of different classification models, including Decision Trees, Logistic Regression, and Support Vector Machines (SVM).

### Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Data Preprocessing](#data-preprocessing)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
5. [Feature Engineering](#feature-engineering)
6. [Classification Models](#classification-models)
7. [Evaluation and Metrics](#evaluation-and-metrics)
8. [Results](#results)
9. [Usage](#usage)
10. [Contributing](#contributing)
11. [License](#license)

### Introduction
The banking industry relies on marketing campaigns to promote various financial products, including term deposits. This project's primary goal is to assist banking institutions in improving their marketing strategies by predicting which clients are more likely to subscribe to a term deposit.

### Dataset
The dataset used in this project is the "Bank Marketing" dataset, which contains various features related to clients, campaigns, and other details. The target variable is binary (yes/no), indicating whether the client subscribed to a term deposit.

### Data Preprocessing
- The dataset is loaded and inspected for missing values and data types.
- Unknown values and placeholders are replaced with NaN (Not a Number).
- Columns with more than 80% of the records with missing values are dropped.
- Rows with missing values are removed.
- Special characters in the 'job' column are replaced.
- Label encoding is applied to the target variable 'y' (binary classification), and one-hot encoding is used for categorical variables.
- Highly correlated features are identified and removed.

### Exploratory Data Analysis (EDA)
- The distribution of numerical and categorical columns is visualized.
- The count of clients subscribing to term deposits is explored.

### Feature Engineering
- Feature selection and engineering are performed to prepare the data for modeling.
- Correlation analysis is used to remove highly correlated features.

### Classification Models
Three classification models are implemented and evaluated:
1. **Decision Tree Classifier**
2. **Logistic Regression**
3. **Support Vector Machine (SVM) Classifier**

### Evaluation and Metrics
The models are evaluated based on the following metrics:
- Accuracy
- Precision
- Recall
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- Confusion Matrix

### Results
The results of the classification models are summarized, and a receiver operating characteristic (ROC) curve is plotted for each model, indicating the area under the curve (AUC).

### Usage
1. Clone the repository or access the original Jupyter Notebook on Colaboratory by following the link provided at the beginning of this file.
2. Run the Jupyter Notebook to execute the code and explore the results.

### Contributing
Contributions and suggestions for improvements are welcome! If you have ideas for enhancing the analysis or find any issues, please feel free to submit a pull request or open an issue on the repository.
