# Homework-2
ELE489 - Homework 2
# Decision Tree for Banknote Authentication

This repository contains a Google Colab notebook (`decision_tree.ipynb`) that demonstrates the implementation of a decision tree algorithm on the Banknote Authentication Dataset from the UCI Machine Learning Repository.

## Overview

- **Image Statistical Measures:** The notebook explains the measures of variance, skewness, kurtosis, and entropy, which are essential for understanding image characteristics.
- **Data Loading & Exploration:** The dataset (1372 instances, 4 features, binary class label) is loaded from a provided ZIP file.
- **Decision Tree Implementation:** The notebook includes:
  - Splitting data into training and testing sets.
  - Training a `DecisionTreeClassifier` with hyperparameter tuning (`max_depth`, `min_samples_split`, `criterion`).
  - Evaluating the model using accuracy, precision, recall, and F1-score.
  - Plotting the confusion matrix, decision tree visualization, and feature importance.
- **Model Reflection:** A discussion/comment on the suitability of decision trees for this dataset.

## Instructions to Run

1. Open `decision_tree.ipynb` in Google Colab.
2. Ensure that the `banknote+authentication.zip` file is available in the Colab session.
3. Run all the cells sequentially to load the data, train the model, and visualize the results.
