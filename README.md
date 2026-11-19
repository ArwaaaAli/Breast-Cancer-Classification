# Breast Cancer Classification Using Machine Learning

## Project Overview

This project focuses on classifying breast tumors as Benign (B) or Malignant (M) using Machine Learning techniques.

The project uses the Breast Cancer Wisconsin (Diagnostic) dataset from the UCI Machine Learning Repository. Several Machine Learning models were implemented, trained, and evaluated to identify the best-performing model.

## Dataset

The dataset contains:

- 569 samples.
- 30 numerical features.
- 1 target variable (Diagnosis).

The features describe characteristics of cell nuclei, including radius, texture, perimeter, area, smoothness, and concavity.

## Project Objectives

- Explore and understand the dataset.
- Perform data cleaning and preprocessing.
- Apply feature engineering.
- Analyze feature relationships and importance.
- Develop and compare Machine Learning models.
- Evaluate model performance.

## Machine Learning Models

Three classification models were implemented:

1. Logistic Regression
2. Random Forest
3. Neural Network (MLP)

## Methodology

The project includes the following steps:

- Data Cleaning and Exploration
- Feature Engineering
- Data Splitting (70% Training, 15% Validation, 15% Testing)
- Feature Scaling
- Model Training
- Hyperparameter Optimization using GridSearchCV
- Model Evaluation and Comparison

## Results

The best-performing model was Logistic Regression.

### Test Performance

| Metric | Score |
|---|---:|
| Accuracy | 98.84% |
| Precision | 96.97% |
| Recall | 100% |
| F1-score | 98.46% |
| ROC-AUC | 1.00 |

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Repository Contents

- `Breast_Cancer_Classification_DS471.ipynb`: Complete project notebook.
- `DS471 Project.docx`: Project report in Word format.
- `DS471 Project.pdf`: Project report in PDF format.
- `README.md`: Project description and documentation.

## Dataset Source

[Breast Cancer Wisconsin (Diagnostic) Dataset - UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)

## Disclaimer

This project is for educational purposes only and is not intended to replace professional medical diagnosis.

## Project Team

- Arwa Alyami
- Mashael Alaftan
- Rana Alwakeel
- Manal Alnazawi
