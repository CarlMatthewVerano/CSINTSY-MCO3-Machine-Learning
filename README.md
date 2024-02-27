# CSINTSY-MCO3-Machine-Learning

# Fetal Health Classification Machine Learning Project

## Overview
This project utilizes machine learning algorithms to classify fetal health into three categories: normal, suspect, and pathological. It is a response to the high infant mortality rates and aims to provide early warnings for fetuses that may require immediate medical attention.

## Dataset
The dataset, sourced from Kaggle, includes various features such as baseline fetal heart rate, accelerations, fetal movements, and contractions. The goal is to use these quantitative characteristics to predict the health status of a fetus. The dataset includes the following features:

- Baseline Fetal Heart Rate (FHR)
- Number of accelerations per second
- Number of fetal movements per second
- Number of uterine contractions per second
- And several other metrics related to fetal health

## Methodology
The methodology involves preprocessing the data using Pandas and scaling features with Scikit-learn's `StandardScaler()`. Machine learning models implemented include logistic regression and neural networks to handle the multi-class classification problem.

## Usage
To run the machine learning models:
1. Ensure you have Python and the necessary libraries installed (Pandas, Scikit-learn).
2. Load the dataset and run the preprocessing steps.
3. Train the logistic regression and neural network models.
4. Evaluate the models based on the test data.
