
# Job Salary Prediction

## Introduction
This project explores the potential of using unlabeled data to improve job salary prediction through semi-supervised learning and self-training. We analyze a dataset provided by Bhola et al. (2020), which includes labeled and unlabeled job descriptions. The goal is to enhance model performance by leveraging the unlabeled data effectively.

## Literature Review
We review relevant literature on the importance of data, especially labeled and unlabeled data, in machine learning. We discuss data augmentation techniques, such as pseudo-labeling, and the benefits of active learning versus self-training in semi-supervised learning.

## Method
Data Pre-processing
We preprocess the dataset to separate labeled and unlabeled data. We analyze the frequency distribution of salary bins and the impact of feature representation on model performance.

## Model Selection
We employ various classification models, including Gaussian Naive Bayes, Decision Tree, K-Nearest Neighbors, Logistic Regression, and Multi-layer Perceptron. We compare their performance based on accuracy.

## Feature Representation Selection
We evaluate three feature representations: raw, TFIDF, and embedding. We analyze their impact on model accuracy and select the most suitable representation.

## Model Tuning
Hyperparameter optimization is performed using grid search and random search to fine-tune the models.

## Self-Training
We apply self-training to augment the labeled data with pseudo-labels from unlabeled data. We explore different thresholds for self-training.

## Results
We present the results of self-training and analyze the confusion matrices before and after self-training. We also compare the accuracy of different models after self-training.

## Critical Analysis
We critically analyze the results, discussing the impact of using the wrong model and the limitations of self-training due to the limited labeled dataset.

## Conclusion
In conclusion, our study indicates that leveraging unlabeled data for job salary prediction may not significantly improve model performance due to challenges such as error propagation. However, there is potential for further exploration of different models and techniques in the future.
## How to execute the program

Chooose the file job Salary Prediction.ipynb

Simply click on the "Run all" button, and the program will automatically execute.
## Datasets

Training dataset : 13,902 job descriptions include 8000 labeled datasets and 5902 unlabeled datasets

Usage:  apply in semi-supervised learning or unsupervised learning approaches.

Development dataset : include 1738 label job descriptions

Usage: for model selection and tuning

Test dataset : include 1,737 label job descriptions

Usage: for Kaggle competition
