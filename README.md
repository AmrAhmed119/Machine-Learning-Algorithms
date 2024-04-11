# 🖥️ Machine Learning Algorithms

This repository contains implementations and documentation for machine learning algorithms applied to various applications.

## 🔸 Assignment 1: Dimensionality Reduction - Face Recognition

### Datasets

- **Face Images**, Download from [Kaggle](https://www.kaggle.com/kasikrit/att-database-of-faces/).
- **Non-Face Images**, Download from [Kaggle](https://www.kaggle.com/datasets/theblackmamba31/landscape-image-colorization) 

### Description

In this assignment, we'll Perform face recognition 🎭 using the ORL dataset, comprising 40 subjects with 10 grayscale images each (92x112 pixels). The assignment entails:

1. **Data Preparation**: Convert images to vectors, generate Data Matrix (D) and Label vector (y).
2. **Dataset Splitting**: Divide data into training and test sets (5 instances per person).
3. **PCA Classification**: Compute projection matrix U for different alpha values, report accuracy.
4. **LDA Classification**: Implement LDA with modifications for multiclass, compare with PCA.
5. **Classifier Tuning**: Vary K-nearest neighbors, plot accuracy against K.
6. **Face vs. Non-face Images**: Attempt face vs. non-face classification, analyze results.
7. **Bonus**: Explore different training/test splits, compare with kernel PCA - LDA variation.


## 🔸 Assignment 2: Daily and Sports Activity Detection

### Datasets

- **Daily and Sports Activities**, Download from [Kaggle](https://www.kaggle.com/datasets/obirgul/daily-and-sports-activities) 

### Description

In this assignment, we'll delve into the exciting domain of  daily and sports activity  detection using motion sensor data 🏃‍♂️🏋️‍♂️. The assignment entails:

1. **Download Dataset and Understand the Format**: We have 19 activities and for each data point we have 125x45 label vector and to reduce it we either perform PCA, LCA or computer the mean for each column.   
2. **Clustering Using K-Means**: Implement K-Means clustering algorithm and apply it to segment the activity data.
3. **Normalized Cut**: Implement the Normalized Cut algorithm to cluster the activity data into 19 clusters and compare results with K-Means.
4. **Evaluation**: Assess the model's performance using metrics such as precision, recall, F1 score, and conditional entropy.
5. **New Clustering Algorithm - DBscan**: We've implemented DBscan and compared it with K-Means and Normalized Cut.
