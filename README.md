# AI/ML Matrimony Recommendation & Prediction System

## Overview

This project implements an AI/ML-based matrimony system consisting of:

1. **Matchmaking Recommendation Engine**

   * Recommends Top 5 compatible profiles for each user
   * Uses profile similarity and interest matching

2. **Interest Acceptance Prediction Model**

   * Predicts whether a matrimony interest request will be accepted
   * Uses Machine Learning classification techniques

The project demonstrates:

* Data preprocessing
* Feature engineering
* Recommendation systems
* Cosine similarity
* Machine learning classification
* Model evaluation

# Features

## Matchmaking Recommendation System

* Opposite gender profile matching
* Interest-based similarity matching
* Profile vector generation
* Cosine similarity recommendation engine
* Top 5 recommendations per user

## Acceptance Prediction System

* Logistic Regression classifier
* Binary classification (Accepted / Rejected)
* Feature scaling and preprocessing
* Accuracy, Precision, Recall evaluation
* Custom prediction support

---

# Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Google Colab

---

# Recommendation System Workflow

## 1. Data Preprocessing

* Converted categorical data using One Hot Encoding
* Converted interests using MultiLabelBinarizer
* Scaled numeric features using MinMaxScaler

## 2. Feature Engineering

Generated:

* Encoded categorical vectors
* Interest vectors
* Normalized numerical vectors

## 3. Similarity Calculation

Used Cosine Similarity to calculate similarity between users.

The system:

* filters opposite gender profiles
* calculates similarity scores
* returns Top 5 most similar users

---

# Acceptance Prediction Workflow

## 1. Data Preprocessing

* Removed unnecessary columns
* Handled feature scaling
* Prepared training and testing data

## 2. Model Building

Used:

* Logistic Regression

## 3. Model Evaluation

Evaluated using:

* Accuracy
* Precision
* Recall
* Confusion Matrix

---

# Visualizations

The project includes:

* User similarity heatmap
* Confusion matrix visualization
* Recommendation score tables

---

# Sample Output

## Recommendation Output

```python
User 1 -> [8, 6, 2, 4, 10]
User 2 -> [5, 9, 1, 7, 3]
```

## Prediction Output

```python
Accepted = 1
```

---

# Assumptions

* Only opposite gender profiles are matched
* Equal feature importance is assumed
* Interests strongly influence recommendations
* Dataset contains no missing values


# Business Understanding

This project simulates how modern matrimony platforms can use:

* profile similarity
* demographic compatibility
* machine learning
* recommendation systems

This project is developed for educational and assignment purposes.
