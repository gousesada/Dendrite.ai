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

## Requirements
- Python 3.7 or above
- Necessary Python libraries listed in `requirements.txt`


