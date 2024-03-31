
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
9. [How to Use](#how-to-use)
10. [License](#license)
11. [Acknowledgments](#acknowledgments)

## Introduction
This research focuses on analyzing customers' default payments in Taiwan, with the aim of comparing the predictive accuracy of the probability of default among six data mining methods. In the field of risk management, understanding the nuanced probability of default is crucial for identifying credible versus non-credible clients. This project explores various data mining techniques to estimate the real probability of default, providing valuable insights for financial institutions.

## Dataset Information
The dataset used in this study comprises detailed customer payment records from Taiwan, including demographic information and payment histories. The novel Sorting Smoothing Method was introduced to estimate the actual probability of default, serving as the foundation for comparing different predictive models.

## Objectives
- To compare the predictive accuracy of six different data mining methods in estimating the probability of default among customers in Taiwan.
- To evaluate the effectiveness of the Sorting Smoothing Method in estimating the real probability of default.
- To determine which data mining technique provides the most accurate estimation of default probability, thereby aiding in risk management and decision-making processes.

## Project Background
Accurate prediction of customers' default probabilities is a significant challenge in risk management. Traditional binary classification approaches—labeling clients as either credible or not credible—are often insufficient for nuanced financial decision-making. This research introduces a more sophisticated approach, employing the Sorting Smoothing Method alongside simple linear regression to better estimate default probabilities.

## Methodology
- **Data Preprocessing:** Utilization of customer payment records, including demographic and payment history data.
- **Data Mining Techniques:** Exploration of six data mining methods, including artificial neural networks, to predict the probability of default.
- **Sorting Smoothing Method:** Application of this novel method to estimate the real probability of default, using it as the response variable in a simple linear regression model.

## Results
The analysis revealed that the forecasting model produced by the artificial neural network displayed the highest coefficient of determination, indicating its superior accuracy in estimating the real probability of default. The model's regression intercept is notably close to zero, and its regression coefficient nearly one, suggesting that artificial neural networks outperform other data mining techniques in predicting default probabilities.

## Technologies Used
- **Python/R:** For data processing, analysis, and implementation of machine learning models.
- **TensorFlow/Keras:** For constructing and training artificial neural network models.
- **Scikit-learn:** For implementing other data mining methods and performing linear regression analysis.
- **Pandas/Numpy:** For data manipulation and numerical computations.

## Tech Stack
This project utilizes a robust tech stack designed for advanced data analysis and predictive modeling:
- **Programming Languages:** Python
- **Machine Learning Libraries:** TensorFlow, Keras, Scikit-learn
- **Data Processing:** Pandas, Numpy
- **Development Environment:** Jupyter Notebooks 


Make sure the "How to Use" section is filled with detailed, step-by-step instructions that are specific to your project setup. This will ensure that others can easily replicate your work and contribute to the project if they wish. This comprehensive README provides a clear overview of your project's objectives, methodology, and the technologies used, making it easier for readers to understand and engage with your research.
