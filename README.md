Dendrite.ai Screening Task
This repository contains the solution to the Dendrite.ai Data Science Internship Screening Task. The project demonstrates the implementation of a machine learning pipeline for automated preprocessing, feature engineering, and model training using the Scikit-learn library.

Table of Contents
Overview
Features
Project Structure
Requirements
Execution
Methodology
Results
License
Overview
The objective of this project is to create a robust machine learning pipeline that automates:

Feature handling
Dimensionality reduction
Hyperparameter tuning
Model selection
The task parameters are dynamically read from a configuration file, and the project supports both classification and regression tasks.

Features
Automated pipeline creation based on configuration files.
Supports dynamic feature engineering using custom transformers.
Hyperparameter optimization using GridSearchCV.
Easily configurable for different datasets and algorithms.
Project Structure
bash
Copy code
Dendrite.ai_Task/
│
├── main.py                     # Entry point for the application
├── Code_File.ipynb             # Jupyter Notebook with step-by-step execution
├── algoparams_from_ui.json     # Configuration file for pipeline parameters
├── iris.csv                    # Sample dataset (Iris dataset)
├── requirements.txt            # Python dependencies
├── Screening Test - DS.docx    # Task description document
├── LICENSE                     # License information
└── README.md                   # Project documentation
Requirements
Python 3.7 or above
Necessary Python libraries listed in requirements.txt
Install the dependencies using:

bash
Copy code
pip install -r requirements.txt
Execution
Clone the repository:
bash
Copy code
git clone https://github.com/gousesada/Dendrite.ai_Task.git
cd Dendrite.ai_Task
Ensure the required dependencies are installed.
Run the main Python script:
bash
Copy code
python main.py
Modify the algoparams_from_ui.json file to customize the pipeline configuration.
Methodology
Parameter Loading: Configuration parameters for the pipeline are loaded from the JSON file.
Data Preprocessing:
Features are handled dynamically based on task requirements.
Dimensionality reduction techniques are applied.
Pipeline Creation:
Feature handling layer.
Feature reduction layer.
Estimator layer (classification or regression models).
Model Tuning: Hyperparameter optimization using GridSearchCV.
Prediction: Predictions are made on the test set, and results are evaluated using accuracy for classification tasks or RMSE for regression tasks.
Results
The best model and its parameters are saved after optimization. Performance metrics are logged for evaluation.

License
This project is licensed under the MIT License.
