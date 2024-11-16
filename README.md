# Dendrite.ai Screening Task

This repository contains the solution to the Dendrite.ai Data Science Internship Screening Task. The project demonstrates the implementation of a machine learning pipeline for automated preprocessing, feature engineering, and model training using the Scikit-learn library.

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Project Structure](#project-structure)
4. [Requirements](#requirements)
5. [Execution](#execution)
6. [Methodology](#methodology)
7. [Results](#results)
8. [License](#license)

## Overview
The objective of this project is to create a robust machine learning pipeline that automates:
- Feature handling
- Dimensionality reduction
- Hyperparameter tuning
- Model selection

The task parameters are dynamically read from a configuration file, and the project supports both classification and regression tasks.

## Features
- Automated pipeline creation based on configuration files.
- Supports dynamic feature engineering using custom transformers.
- Hyperparameter optimization using GridSearchCV.
- Easily configurable for different datasets and algorithms.

## Project Structure
The project follows a modular approach with the following file structure:
- **main.py**: The main Python script that runs the entire pipeline.
- **Code_File.ipynb**: A Jupyter Notebook providing a detailed breakdown of the task, including code, explanations, and outputs.
- **algoparams_from_ui.json**: JSON configuration file containing parameters for the pipeline (e.g., algorithm settings, hyperparameters).
- **iris.csv**: A sample dataset (the Iris dataset) used for testing and experimentation within the project.
- **requirements.txt**: A list of Python dependencies required for the project, installable via `pip`.
- **Screening Test - DS.docx**: A document that contains the details and description of the task for which this project is created.
- **LICENSE**: Contains the licensing details for the project.
- **README.md**: This file, providing documentation and guidance on how to use and contribute to the project.
## Execution
Clone the repository:
git clone https://github.com/gousesada/Dendrite.ai_Task.git

## Methodology

The following steps outline the methodology used in this project:

1. **Parameter Loading**: 
   - Configuration parameters for the pipeline are loaded from the `algoparams_from_ui.json` file, which contains key settings such as model parameters, preprocessing options, and algorithm configurations.

2. **Data Preprocessing**: 
   - Features are dynamically handled based on the task requirements, allowing for flexibility and automation.
   - Dimensionality reduction techniques, such as PCA or feature selection methods, are applied to improve model performance and reduce overfitting.

3. **Pipeline Creation**:
   - **Feature Handling Layer**: This layer is responsible for handling missing values, encoding categorical features, and scaling numerical features.
   - **Feature Reduction Layer**: Techniques like PCA (Principal Component Analysis) or other methods are used to reduce the dimensionality of the dataset, improving model efficiency and training time.
   - **Estimator Layer**: This layer contains the machine learning models (classification or regression algorithms), which are selected based on the task (e.g., Decision Trees, Random Forests, or Linear Regression).

4. **Model Tuning**:
   - Hyperparameter optimization is performed using GridSearchCV, which tests different combinations of hyperparameters to find the best model configuration.

5. **Prediction**:
   - Predictions are made on the test set, and the model's performance is evaluated using appropriate metrics such as accuracy for classification tasks or RMSE (Root Mean Squared Error) for regression tasks.

## Results
The best model and its parameters are saved after optimization. Performance metrics are logged for evaluation.
## Requirements
- Python 3.7 or above
- Necessary Python libraries listed in `requirements.txt`


