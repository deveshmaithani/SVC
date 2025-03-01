# SVC
Support Vector Classifiers


## Overview
This project implements Support Vector Classifiers (SVC) using different kernel functions. We trained and evaluated models using Linear, RBF, Polynomial, and Sigmoid kernels and optimized them using GridSearchCV for hyperparameter tuning.

## Project Features
✔ Implemented SVC with multiple kernels: Linear, RBF, Polynomial, and Sigmoid.
✔ Hyperparameter tuning using GridSearchCV for optimal performance.
✔ Decision boundary visualization for better interpretability.
✔ Model evaluation using accuracy, confusion matrix.

## Technologies Used
Python
Scikit-Learn
Matplotlib & Seaborn
NumPy & Pandas

## Hyperparameter Tuning
Performed GridSearchCV on:

C (Regularization parameter)
gamma (Kernel coefficient for non-linear kernels)
degree (Degree of the polynomial kernel)

Best parameters were selected and applied to the final model.

## Results & Observations
The RBF kernel performed best for our dataset.
GridSearchCV improved accuracy and generalization.
Decision boundary visualization helped understand kernel effects.
