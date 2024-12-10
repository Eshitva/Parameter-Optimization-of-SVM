
# NuSVC Optimization Using GridSearchCV

This project demonstrates the use of **Nu-Support Vector Classification (NuSVC)** for digit classification. The script employs the `digits` dataset from Scikit-learn, performs hyperparameter optimization using **GridSearchCV**, and evaluates the model's performance on a test set.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Results](#results)
- [Visualization](#visualization)
- [Acknowledgments](#acknowledgments)

## Overview
The objective of this script is to optimize the parameters of NuSVC to achieve high classification accuracy on the digits dataset. The script evaluates multiple combinations of hyperparameters and identifies the best-performing configuration.

## Features
- Loads and preprocesses the `digits` dataset.
- Splits data into training and test sets (70%-30%).
- Optimizes NuSVC hyperparameters (`nu`, `kernel`, `gamma`, and `degree`) using **GridSearchCV**.
- Evaluates and prints:
  - Best hyperparameters.
  - Best cross-validation accuracy.
  - Test set accuracy.
- Visualizes the convergence of cross-validation accuracy over iterations.

## Setup Instructions
1. Clone the repository or download the script.
2. Ensure the following Python libraries are installed:
   - `numpy`
   - `matplotlib`
   - `scikit-learn`

   Install these libraries using pip:
   ```bash
   pip install numpy matplotlib scikit-learn
   ```

3. Run the script:
   ```bash
   python nusvc_gridsearch.py
   ```

## Usage
1. Load the dataset and split it into training and test sets.
2. Define the parameter grid for NuSVC, which includes:
   - `nu`
   - `kernel`
   - `gamma`
   - `degree`
3. Use GridSearchCV to find the best parameters.
4. Evaluate the best model on the test set.
5. Visualize convergence results.

## Results
- Best Parameters: Displayed in the script output.
- Best Cross-Validation Accuracy: Displayed in the script output.
- Test Set Accuracy: Displayed in the script output.

## Visualization
The script generates a convergence graph of cross-validation accuracy over iterations.

## Acknowledgments
- The `digits` dataset is provided by Scikit-learn.
- Scikit-learn documentation was used as a reference for using NuSVC and GridSearchCV.

---
