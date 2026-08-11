# Wine Quality Prediction

## AICTE Oasis Infobyte Internship – Data Analytics

### Task: Wine Quality Prediction

## 📌 Project Overview

This project focuses on predicting wine quality based on its physicochemical properties using machine learning classification algorithms.

The dataset contains chemical characteristics such as acidity, density, sulphates, and alcohol content. Wine quality scores are grouped into three categories: Low, Medium, and High.

## 🎯 Objective

The objective of this project is to build and compare multiple classification models for predicting wine quality.

The following models were implemented:

- Random Forest Classifier
- SGD Classifier
- Support Vector Classifier (SVC)

## 📊 Dataset

The dataset used is `WineQT.csv`.

It contains:

- 1,143 wine records
- 11 physicochemical features
- Wine quality score
- ID column

There are no missing values in the dataset.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## 🔍 Data Analysis

The project includes:

- Dataset inspection
- Missing-value analysis
- Descriptive statistics
- Wine quality distribution
- Correlation analysis
- Class imbalance analysis
- Feature preparation

## ⚙️ Data Preprocessing

Wine quality scores were grouped into three categories:

- Low: Quality ≤ 5
- Medium: Quality = 6
- High: Quality ≥ 7

The dataset was divided into training and testing sets using an 80/20 split with stratification.

Feature standardization was performed using `StandardScaler`.

## 🤖 Machine Learning Models

Three classification models were trained:

### 1. Random Forest

A Random Forest classifier was used to predict wine quality categories and identify important features.

### 2. SGD Classifier

A Stochastic Gradient Descent classifier was trained using standardized features.

### 3. Support Vector Classifier

An SVC model with an RBF kernel was used for classification.

## 📈 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Classification Report
- Confusion Matrix

The performance of all three models was compared using a comparison table and visualization.

## 🌟 Feature Importance

Random Forest feature importance was analyzed to identify which chemical properties contributed most to the prediction of wine quality.

## 💡 Key Insights

- Wine quality categories are imbalanced, with fewer high-quality wine samples.
- Chemical properties can be used to classify wines into different quality categories.
- Model performance varies between Random Forest, SGD, and SVC.
- Feature importance provides useful information about the chemical characteristics associated with wine quality.

## 📁 Project Structure

```text
DataAnalytics-L2-WineQuality/
│
├── WineQT.csv
├── Wine_Quality_Prediction.ipynb
└── README.md