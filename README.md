
# Loan Eligibility Prediction

Developed a machine learning model that predicts loan default probabilities for bank customers. The dataset used to train the model was obtained from Kaggle and included various features such as age, income, loan amount, credit history, and loan eligibility status (default or not). After extensive data preprocessing and model training, the Logistic Regression model demonstrated promising predictive capabilities by achieving an accuracy of 71.59%.

## Dataset

The dataset used in this project sourced from Kaggle (https://www.kaggle.com/datasets/vikasukani/loan-eligible-dataset) contains information about loan applicants including their gender, marital status, income, credit history, etc. 

## Exploratory Data Analysis (EDA)

The EDA section of the notebook explores the dataset to understand its structure, distribution, missing values, and correlations between features. It includes visualizations such as histograms, box plots, and correlation matrices.

## Data Preprocessing

Before training the machine learning models, the dataset undergoes preprocessing steps including handling missing values, encoding categorical variables, scaling features, and splitting the data into training and testing sets.

## Model Building and Evaluation

### Logistic Regression

- **Accuracy**: 71.60%
- **Precision**: 0.6357
- **Recall**: 0.9880
- **F1-score**: 0.7736
- **Area under the ROC curve (AUC)**: 0.721

### K-Nearest Neighbors (KNN)

- **Best Accuracy**: 71.60%

## Model Comparison

The performance of the logistic regression and KNN models is compared based on metrics such as accuracy, precision, recall, and F1-score.



