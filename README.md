# ML-add-health-depression
This repository contains the code and analyses for a study predicting depressive symptoms and clinical depression using Add Health longitudinal data. The goal is to test whether machine learning models can outperform traditional methods like Logistic Regression in predicting depression outcomes across adolescence and adulthood.

We trained five models of varying complexity — Logistic Regression, Random Forest, XGBoost, Support Vector Machine, and Neural Network — using early-life predictors collected during adolescence (ages 12–18). Predictors include environmental, psychosocial, and genetic (polygenic score) variables measured in Waves I and IV of Add Health.

The workflow includes:

Data preprocessing and feature construction

Model training and hyperparameter tuning

Evaluation of predictive performance (ROC-AUC, accuracy)

Feature importance and sensitivity analyses

Our findings show that XGBoost achieved the highest performance, though improvements over Logistic Regression were modest. Early-life environmental and psychosocial factors were strong predictors of both depressive symptoms and clinical depression, while polygenic scores added minimal predictive power.

This project highlights how adolescent data can inform long-term mental health predictions and demonstrates the practical limits of applying machine learning to large-scale social and genetic datasets.
