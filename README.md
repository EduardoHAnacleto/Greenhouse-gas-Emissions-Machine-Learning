# Greenhouse-gas-Emissions-Machine-Learning
Machine Learning models predicting greenhouse gas emissions with Random Forest, Decision Tree, SVM and LightGBM (Stacking RF+SVM)

Project developed for the Machine Learning assignment during the master's degree program (Whitecliffe College, 2024)

# Abstract

This study explores the use of machine learning models to predict greenhouse
gas emissions, focusing specifically on Methane (CH4) and Nitrous Oxide (N2O)
emissions. Utilizing a dataset from the Greenhouse Gas Reporting Program
(GHGRP) obtained from the Kaggle repository, the research aimed to under-
stand emission patterns over time and forecast future emissions. Challenges
included addressing the complexities of categorical variables and the high vari-
ance present in the data. Four models were developed and evaluated: Decision
Trees, Random Forest, Support Vector Machines (SVM), and a stacked model
combining Random Forest and SVM with LightGBM. Each model underwent
hyperparameter tuning and was assessed using Mean Absolute Error (MAE),
Mean Squared Error (MSE), and R2, with results validated through 10-fold Cross-
Validation. The LightGBM stacking model achieved the highest cross-validation
R2 values, demonstrating a more balanced residual distribution compared to
other models. In contrast, the Decision Tree and Random Forest models dis-
played more variance in their predictions, while the SVM faced challenges with
non-linear relationships. These findings underscore the potential of ensemble
methods in improving predictive accuracy for GHG forecasting. However, lim-
itations related to data scope, computational cost, and feature complexity can
drive the conclusion of further need for research to refine these models for more
robust environmental prediction machine learning models

#Dataset found on:
Shahid, S. S. (2024). Emissions by unit and fuel type: Detailed anal-
ysis of emissions by unit and fuel type: A comprehensive break-
down. https://www.kaggle.com/datasets/shayanshahid997/emissions-by-unit-and-fuel-type?select=Industry+Type.csv.
CC0: Public Domain, Accessed: September 5, 2024.
