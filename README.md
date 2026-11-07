# Classifying Smokers Using Biological Health Indicators

A machine learning classification project investigating whether an individual's smoking status can be predicted using biological health indicators. Developed as a group project for DSCI 100 at the University of British Columbia.

## Project Overview

This project explores the relationship between smoking status and four biological indicators:

- **AST (Aspartate Aminotransferase):** Liver enzyme associated with liver function.
- **ALT (Alanine Aminotransferase):** Liver enzyme associated with liver function.
- **Fasting Blood Sugar:** Blood glucose concentration after fasting.
- **Triglycerides:** A type of fat found in the bloodstream.

Using the *Body Signal of Smoking* dataset, we developed a K-Nearest Neighbours (KNN) classification model to predict whether an individual is a smoker or nonsmoker.

## Methods

- **Data Preprocessing:** Cleaned and standardized health indicators from a dataset of 55,962 observations, selecting a balanced sample of 1,000 individuals.
- **Exploratory Data Analysis:** Examined relationships between biological indicators and smoking status using summary statistics and visualizations.
- **Model Development:** Implemented a KNN classifier using R and the `tidymodels` framework.
- **Hyperparameter Tuning:** Used 5-fold cross-validation to identify the optimal number of neighbours (K = 155).
- **Model Evaluation:** Assessed classification performance using accuracy, precision, recall, and a confusion matrix.

## Results

The final KNN model achieved:

| Metric | Result |
|---|---|
| Test Accuracy | 64.8% |
| Precision | 63.7% |
| Recall | 68.8% |
| Optimal K | 155 |

The results suggest that biological indicators provide some predictive information about smoking status, although substantial overlap between smokers and nonsmokers limits classification accuracy.

## Technologies

- **Language:** R
- **Environment:** Jupyter Notebook
- **Libraries:** tidyverse, tidymodels, ggplot2, RColorBrewer
- **Techniques:** KNN Classification, Cross-Validation, Data Preprocessing, Exploratory Data Analysis

## Dataset

[Body Signal of Smoking — Kaggle](https://www.kaggle.com/datasets/kukuroo3/body-signal-of-smoking/data)

## Contributors

Developed collaboratively by Elena Greenall, Noah Hynds, and Dillon Li as part of DSCI 100 at the University of British Columbia.
