# Diabetes Prediction with Machine Learning

This repository contains an exploratory data analysis (EDA) and predictive modeling project for diabetes diagnosis. The main objective is to explore the data, identify patterns, and create a machine learning model capable of predicting the diagnosis based on the patients' clinical characteristics.

## 👤 Author

Pedro Gabriel Fonseca

## 📄 Project Description

The project employs a supervised learning approach to predict a diabetes diagnosis based on variables such as glucose levels, BMI, blood pressure, and age, among other medical features.

## 🔧 Tools Used

- **Language:** Python
- **Libraries:**
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `plotly (plotly.express)`
  - `scikit-learn (model_selection, preprocessing, metrics, ensemble, neighbors, svm, tree, neural_network)`

## 📊 Project Stages

1️⃣ **Data Collection and Cleaning**
  - The dataset was loaded and cleaned to ensure information integrity.
  - Removal of inconsistent values and outlier handling using the **Local Outlier Factor (LOF)** algorithm.

2️⃣ **Exploratory Data Analysis (EDA)**
  - Visualizations using `matplotlib`, `seaborn`, and `plotly` to analyze distributions and correlations.
  - Generation of heatmaps, histograms, and scatter plots to better understand data patterns.

3️⃣ **Machine Learning Prediction**
  - Implementation and comparison of various models, including:
    - Logistic Regression
    - K-Nearest Neighbors (KNN)
    - Support Vector Machine (SVM)
    - Decision Trees
    - Random Forest
    - Gradient Boosting
    - Artificial Neural Networks (MLPClassifier)
  - Model evaluation using metrics such as accuracy, recall, F1-score, and confusion matrix.
  
   
