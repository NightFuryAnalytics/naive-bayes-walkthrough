# 📌 Naive Bayes Walkthrough Guide in Python

## 🚀 Overview
This guide provides a step-by-step walkthrough of implementing the **Naive Bayes Theorem** in Python, both **from scratch** and using **built-in libraries**. It is designed for beginners in Python and machine learning, with detailed explanations and code comments to ensure easy understanding.

## 📂 Files
- **`golf_data.csv`** → Sample dataset used for training and testing.
- **`Naive Bayes- Walkthrough.ipynb`** → Contains both implementations in comprehensive manner.

# 📜 Implementation Steps
### 1️⃣ **Understanding Naive Bayes**
- Based on **Bayes' Theorem**.
- Assumes **independence** between features.
- Works well for **text classification** and **spam detection**.

### 2️⃣ **From Scratch Implementation**
- Preprocess dataset
- Calculate prior probabilities
- Compute likelihood using word frequencies
- Apply log-probabilities to avoid underflow
- Predict class with the highest probability

### 3️⃣ **Using scikit-learn** (`naive_bayes_sklearn.py`)
- Utilize `GaussianNB`, `MultinomialNB`, or `BernoulliNB`
- Fit model on training data
- Predict and evaluate performance

## 📊 Results & Evaluation
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix & ROC Curve visualization
  
