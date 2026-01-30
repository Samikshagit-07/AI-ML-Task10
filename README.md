# AI-ML-Task10

Handwritten Digit Classification using KNN

Project Overview

This project implements a K-Nearest Neighbors (KNN) classifier to recognize handwritten digits (0-9) using the Scikit-learn digits dataset. The goal was to explore how feature scaling and the choice of K affect model accuracy.

Implementation Steps

Data Loading: Loaded 1,797 images of 8 x 8 pixels.

Preprocessing: Applied StandardScaler to normalize the data, which is essential because KNN relies on Euclidean distance.

K-Tuning: Tested multiple K values (3, 5, 7, and 9) to find the optimal balance between bias and variance.

Evaluation: Generated a confusion matrix to identify specific misclassifications.

Key Results

Best K Value: K=3 (typically provides the highest accuracy for this dataset).
Accuracy: 97%
Confusion Matrix: Most digits were classified correctly, with minor confusion between similar shapes like 1 and 8.
