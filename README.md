# Breast Cancer Prediction using Artificial Neural Networks

This project implements a Breast Cancer Prediction system using an Artificial Neural Network (ANN). It utilizes the `sklearn` library to preprocess the data, perform feature selection, train the ANN model, and evaluate its performance. A Streamlit app is also included for interactive user prediction.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Acknowledgments](#acknowledgments)

---

## Project Overview

This project uses the **Breast Cancer Wisconsin dataset** from the `sklearn.datasets` module. It performs the following steps:
1. **Data Preprocessing**:
   - Converts the dataset into a Pandas DataFrame.
   - Standardizes feature values using `StandardScaler`.
   - Selects the top 10 features based on the ANOVA F-statistic.

2. **Model Training**:
   - Uses an MLPClassifier (ANN) with one hidden layer of 100 neurons and ReLU activation.
   - Trains the model using the Adam optimizer with adaptive learning rates.

3. **Model Evaluation**:
   - Provides accuracy scores, classification reports, and confusion matrices for the training and test datasets.

4. **Interactive Prediction**:
   - Implements a Streamlit-based app where users can provide feature values and receive predictions.

---

## Features

- Preprocesses and selects the most relevant features from the dataset.
- Trains an ANN for binary classification (Benign vs. Malignant tumors).
- Provides interactive prediction capabilities using Streamlit.
- Displays model performance metrics, including accuracy, classification reports, and confusion matrices.

---


