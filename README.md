# Diabetes Prediction Using Machine Learning and Deep Learning Models

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Models Implemented](#models-implemented)
- [Preprocessing](#preprocessing)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Project Overview
This project focuses on predicting the likelihood of diabetes in individuals using both Machine Learning (ML) and Deep Learning (DL) models. The objective is to compare the performance of these models in terms of accuracy and recall, with and without addressing class imbalance using the Synthetic Minority Over-sampling Technique (SMOTE).

## Dataset
The dataset used for this project contains 100,000 anonymized records collected from various countries about a year ago. The data is sourced from Kaggle and includes medical and demographic information for each individual.

- **Source**: [Kaggle Diabetes Dataset](https://www.kaggle.com/)
- **Size**: 100,000 rows, 9 features

## Features
The dataset includes the following features:
- Age
- Gender
- BMI (Body Mass Index)
- Blood Pressure
- Cholesterol Level
- Glucose Level
- Heart Disease
- Hypertension
- Hemoglobin Level

These features are used to predict the likelihood of an individual being diabetic.

## Models Implemented
The project implements the following models:
- **Deep Learning Models**:
  - Multi-Layer Perceptron (MLP)
  - Residual Convolutional Neural Network (Residual CNN)
- **Machine Learning Models**:
  - Logistic Regression
  - Random Forest
  - Decision Tree
  - Naive Bayes

## Preprocessing
Before feeding the data into the models, the following preprocessing steps were applied:
1. **Encoding**: Categorical features were encoded using appropriate techniques.
2. **Normalization**: Features were normalized using a Min-Max scaler.
3. **Class Imbalance Handling**: SMOTE was used to address class imbalance.

## Evaluation Metrics
The models were evaluated using the following metrics:
- **Accuracy**: Proportion of correct predictions.
- **Recall**: Ability to capture all true positive cases.
- **F1 Score**: Balance between precision and recall.
- **Confusion Matrix**: Detailed breakdown of true positives, true negatives, false positives, and false negatives.

## Results
- The Deep Learning models achieved an accuracy of 97% and a recall of 100% without addressing class imbalance.
- When SMOTE was applied, traditional Machine Learning models matched the performance of the Deep Learning models, also achieving 97% accuracy and recall.

These results demonstrate the effectiveness of both ML and DL models in predicting diabetes.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss changes.

## Acknowledgements
Thanks to the Kaggle community for providing the dataset and to all contributors for their support in the development of this project.

