# Breast Cancer Classification Using Machine Learning

## Project Overview

This project is about using machine learning to classify breast tumors as **benign or malignant**.

The main aim of the project is to train different machine learning classification models, compare their results, and find out which model performs the best on the breast cancer diagnostic dataset.

For this project, four different models were used:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest

After comparing the performance of all four models, **Logistic Regression was found to be the best-performing model**.

---

## Problem Statement

Breast cancer diagnosis involves identifying whether a tumor is **benign or malignant** based on different diagnostic features.

In this project, machine learning is used to analyze these features and build models that can classify the tumors into the two categories.

The main problem addressed in this project is to develop and compare different machine learning models and determine which one gives the most reliable classification results.

> **Note:** This project is developed for academic purposes and is not intended to replace professional medical diagnosis.

---

## Objectives

The main objectives of this project are:

- To build a machine learning model that can classify breast tumors.
- To prepare and preprocess the diagnostic dataset.
- To divide the dataset into training and testing data.
- To apply feature scaling before training the models.
- To train different machine learning classification algorithms.
- To compare the performance of the models using suitable evaluation metrics.
- To identify the best-performing model.
- To further evaluate the selected model using ROC-AUC and classification analysis.

---

## Dataset

The project uses a breast cancer diagnostic dataset containing numerical features related to breast tumor samples.

The target variable has two possible classes:

| Class | Meaning |
|------|---------|
| 0 | Benign |
| 1 | Malignant |

The diagnostic features are used as input for training the machine learning models, while the target variable is used to determine the tumor class.

---

## Methodology

The project follows a step-by-step machine learning process, starting from preparing the dataset and ending with selecting the best model.

The overall workflow is:

```text
Dataset
   ↓
Data Preprocessing
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Best Model Selection
