## ![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Supervised ML Regression Challenge

## Introduction

In this exercise, you will be tasked with building a predictive model for insurance costs based on various features from a dataset. This exercise focuses on regression techniques in supervised machine learning. The goal is to achieve the highest R² score on the test data, so be prepared to explore different modeling approaches. It practises the Feature Engineering and Model Tuning lesson: a baseline, feature engineering, pipelines and grid search.

## Getting Started

Open the `main.ipynb` file located in the `your-code` directory. The notebook contains a series of exercises to guide you through the process of data exploration, preprocessing, model training, and evaluation. If you encounter difficulties with one exercise, feel free to move on to the next.

## Dataset

You will find the dataset in the CSV file named `insurance.csv`. The target column to predict is labeled "charges".

## Deliverables

- `main.ipynb` with your responses and code implementations for each exercise.

## Guidelines

- Use `train_test_split` with:
  - `random_state = 42`
  - `test_size = 0.3`

## Resources

- [Machine Learning Basics | Scikit-Learn Documentation](https://scikit-learn.org/stable/supervised_learning.html)
- [Regression metrics | Scikit-Learn Documentation](https://scikit-learn.org/stable/modules/model_evaluation.html#regression-metrics)
- [Pipelines and ColumnTransformer | Scikit-Learn Documentation](https://scikit-learn.org/stable/modules/compose.html)
- [GridSearchCV | Scikit-Learn Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)
- The **Feature Engineering and Model Tuning** lesson (Week 5, Day 1)
