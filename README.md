
# Predictive Accuracy of Default Probabilities

**Table of Contents**
1. [Introduction](#introduction)
2. [Dataset Information](#dataset-information)
3. [Objectives](#objectives)
4. [Project Background](#project-background)
5. [Methodology](#methodology)
6. [Results](#results)
7. [Technologies Used](#technologies-used)
8. [Tech Stack](#tech-stack)

## Introduction
This research focuses on analyzing customers' default payments in Taiwan, aiming to compare the predictive accuracy of the probability of default among different data mining methods. The project explores the estimation of real default probabilities, offering valuable insights for risk management in financial institutions.

## Dataset Information
The study utilizes a dataset consisting of customer payment records from Taiwan. The data includes demographic information and payment histories, which are analyzed to predict the probability of default.

## Objectives
- To assess the predictive accuracy of various data mining methods for estimating customers' default probabilities.
- To utilize the Sorting Smoothing Method to estimate the real probability of default and compare it against predictions.

## Project Background
The challenge of accurately predicting default probabilities is crucial in risk management. This study adopts a sophisticated approach, leveraging data mining techniques to better understand default risks.

## Methodology
- **Data Preprocessing:** Utilization of Pandas and Numpy for data cleaning and preparation.
- **Predictive Modeling:** Implementation of Support Vector Machine (SVM) as the primary data mining technique.
- **Model Evaluation:** Use of Cross-Validation and GridSearchCV from sklearn for model optimization and evaluation.

## Results
The research found that the artificial neural network model, initially considered, was highly effective. However, the focus on SVM, supported by rigorous cross-validation and grid search techniques, provided significant insights into model performance and optimization.

## Technologies Used
- **Pandas/Numpy:** For data manipulation and numerical computations.
- **Matplotlib:** For generating visualizations of the data and results.
- **Sklearn (Scikit-learn):** For machine learning models, including support vector machine, cross-validation, and hyperparameter tuning using GridSearchCV.

## Tech Stack
The detailed tech stack for this project includes:
- **Data Processing and Analysis:** Pandas, Numpy
- **Visualization:** Matplotlib
- **Machine Learning:** Sklearn (for SVM, Cross-Validation, GridSearchCV)
