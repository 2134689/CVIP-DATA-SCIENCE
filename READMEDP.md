****Task-1: Diabetes Prediction [Normal Task Phase-2]****

**Overview**
This repository contains a machine learning project that utilizes Logistic Regression for diabetes prediction. The project is implemented in a Jupyter Notebook and comes with an interactive user interface created using Gradio. The model predicts whether an individual is diabetic or not based on various health-related features.

**Table of Contents**
Introduction
Dataset
Dependencies
Installation
Usage
Model Training
Model Evaluation
Interactive User Interface
Contributing
License

**Introduction**

Diabetes is a prevalent health condition affecting millions of people globally. Early detection and prediction of diabetes are essential for timely medical intervention and effective disease management. This project aims to build a machine learning model using Logistic Regression to predict the likelihood of an individual having diabetes based on features such as glucose level, BMI, blood pressure, age, and others.

**Dataset**

The dataset used for training and testing the model is sourced from kaggle (Diabetes Prediction dataset link on kaggle : https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset). It consists of a collection of samples, each with relevant health-related features and corresponding diabetes status (binary classification).

**Dependencies**

To run the project, you need the following dependencies:

Python 3.x
Jupyter Notebook
Pandas
NumPy
Scikit-learn
Gradio

**Installation**

Clone this repository to your local machine:

bash

Copy code

git clone https://github.com/2134689/CVIP-DATA-SCIENCE.git

Navigate to the project directory:

bash

Copy code

cd Diabetes_Prediction

Install the required dependencies:

bash

Copy code

pip install pandas numpy scikit-learn gradio

**Usage**

Launch Jupyter Notebook:

bash

Copy code

jupyter notebook

Open the Diabetes_Prediction.ipynb notebook.

Follow the instructions in the notebook to explore the dataset, preprocess the data, train the Logistic Regression model, and evaluate its performance.

**Model Training**

The diabetes_prediction.ipynb notebook guides you through the steps of training the Logistic Regression model using the provided dataset. The model is trained on a portion of the data and evaluated on a test set to assess its performance.

**Model Evaluation**

The model's performance is evaluated using various metrics such as accuracy, precision, recall, and F1-score. Additionally, confusion matrix and ROC curve analysis are used to assess the model's predictive capabilities.

**Interactive User Interface**

The model comes with an interactive user interface powered by Gradio. To use the interface:

Run the notebook until the section where the Gradio interface is defined.

The Gradio app will start automatically, allowing you to input health-related features and obtain real-time predictions for diabetes status.

**Contributing**

Contributions to this project are welcome! If you have suggestions for improvements, bug fixes, or additional features, feel free to open an issue or submit a pull request.

**License**

This project is licensed under the MIT License. You are free to use and modify the code for both personal and commercial purposes.

