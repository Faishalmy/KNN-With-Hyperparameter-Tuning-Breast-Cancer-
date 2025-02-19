# KNN With Hyperparameter Tuning Breast Cancer
<p align="justify">
An in-depth research where I integrated expertise in machine learning, mathematics, and optimization techniques to improve classification accuracy. Using Python, this research includes applying data pre-processing to handle outliers and standardizing the dataset to ensure optimal data quality. In addition, a hyperparameter tuning technique through Grid Search is applied to produce a more optimized KNN model in breast cancer classification.
</p>

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Pre-processing](#data-pre-processing)
- [Modeling](#modeling)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Results](#results)
- [Conclusion](#conclusion)
- [Requirements and Library](#requirements-and-library)

## Introduction
<p align="justify">
Breast cancer is one of the most common cancers among women worldwide. Early detection and diagnosis are crucial for effective treatment and improving survival rates. This project utilizes the K-Nearest Neighbors (KNN) algorithm to classify breast cancer cases based on diagnostic data. To improve the model's performance, data pre-processing and hyperparameter tuning using the grid search technique are applied.
</p>

## Dataset
<p align="justify">

The dataset used in this project is the [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)), which contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. The dataset includes the following attributes:
</p>

- ID number
- Diagnosis (M = malignant, B = benign)
- Ten real-valued features computed for each cell nucleus

## Data Pre-processing

Data pre-processing steps include:

1. Feature Selection (based on correlation value)
2. Handling Outliers
3. Feature scaling (normalization or standardization)


## Modeling

<p align="justify">
The K-Nearest Neighbors (KNN) algorithm is implemented for the classification task. The KNN algorithm is a simple, instance-based learning algorithm that classifies a sample based on the majority class of its nearest neighbors.
</p>

## Hyperparameter Tuning

<p align="justify">
Hyperparameter tuning is performed using the grid search technique to find the optimal values for the KNN algorithm's parameters, such as the number of neighbors (k), Class Weighting (e.g., Uniform, Distance), and the distance metric (e.g., Euclidean, Manhattan).
</p>

## Results

<p align="justify">
The performance of the optimized KNN model is evaluated using various metrics, such as accuracy, precision, and recall. The results are compared to the baseline model to demonstrate the improvement achieved through optimization.
</p>

## Conclusion

<p align="justify">
This project demonstrates the effectiveness of data pre-processing and hyperparameter tuning in improving the performance of the KNN algorithm for breast cancer diagnosis. The optimized model provides better classification accuracy and reliability, contributing to more accurate and early diagnosis of breast cancer.
</p>

## Requirements and Library

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
