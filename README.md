# Diabetes Prediction on Pima Indians Diabetes Database using Naive Bayes

**Author:** Kunal Yadav  
**Email:** mailmekunal2002@gmail.com

## Abstract

This project focuses on diabetes prediction using the Pima Indians Diabetes Database. We explore data preprocessing techniques, handle missing values, and detect outliers. After thorough data preparation, we apply the Naive Bayes algorithm for classification. Our model achieves an accuracy of 77.92%. This report discusses data analysis, preprocessing, model creation, and evaluation, offering insights into diabetes prediction.

## Introduction

Diabetes prediction is a critical healthcare task. We aim to predict diabetes in individuals using the Pima Indians Diabetes Database.

## Methods

### Data Preparation

- Loaded the dataset from Google Drive.
- Replaced missing values with medians.
- Handled outliers using percentile clipping.

### Data Analysis

- Explored the dataset's distribution and relationships between variables.
- Visualized the distribution of diabetic and non-diabetic patients.

## Results

- Naive Bayes Model:
  - Accuracy: 77.92%

### Data Visualization

- Utilized box plots to detect outliers.
- Created a heatmap to visualize correlations between features.
- Generated pair plots for a comprehensive analysis of data distribution.

## Discussion

Our analysis reveals that outliers in the "Insulin" attribute required substantial manipulation, which might affect model performance. Consideration should be given to removing this feature from the dataset.

## Conclusion

This project demonstrates the application of Naive Bayes for diabetes prediction. While achieving a commendable accuracy rate, it also highlights the importance of careful data preprocessing and feature selection in healthcare applications.

---
