# Diabetes Prediction Project
This project involves predicting the risk of diabetes using data from the Behavioral Risk Factor Surveillance System (BRFSS) for the years 2015 and 2021. The project utilizes machine learning techniques, specifically Logistic Regression and Random Forest classifiers, to make predictions based on various health and demographic factors.

## Table of Contents
- Introduction
- Datasets
- Preprocessing
- Exploratory Data Analysis (EDA)
- Model Training
- Model Evaluation
- User Interface
- Installation
- Usage
- Contributing
- License
- Acknowledgements
## Introduction
The aim of this project is to develop a machine learning model that can predict whether a person is at risk of diabetes based on various health-related features. The project makes use of data from the BRFSS, which includes a variety of health indicators.

## Datasets
- BRFSS 2015: Behavioral Risk Factor Surveillance System data for the year 2015.
- BRFSS 2021: Behavioral Risk Factor Surveillance System data for the year 2021.
- The datasets include features such as BMI, general health status, mental health, physical health, and other health behaviors.

## Preprocessing
- Combined the 2015 and 2021 datasets into a single DataFrame.
- Removed irrelevant features to reduce dimensionality.
- Checked and confirmed that there are no missing values in the reduced dataset.
- Optimized data types to reduce memory usage.
- Converted binary columns to boolean values for better processing.
## Exploratory Data Analysis (EDA)
- Performed EDA to understand the distribution and relationships of the features in the dataset:

- Plotted histograms of general health, physical health, and mental health by diabetes status.
- Plotted scatter plots of age vs. BMI and age vs. general health by diabetes status and sex.
- Analyzed the distributions of various features to gain insights.
## Model Training
- Trained a logistic regression model to predict diabetes risk.
- Trained a random forest classifier to predict diabetes risk.
- Split the data into training and testing sets.
- Normalized numerical features using MinMaxScaler.
- Evaluated the models using accuracy, confusion matrix, and classification report.
## Model Evaluation
- Evaluated the performance of the logistic regression and random forest models using cross-validation.
- Reported the average prediction scores for both models.
- Analyzed the confusion matrices and classification reports to understand the models' performance.
## User Interface
- Developed an interactive user interface using ipywidgets to allow users to input health information and receive a prediction of diabetes risk.
- Created widgets for various features such as BMI, age, general health, and more.
- Provided a button to make predictions and display the results.
## Installation
To run this project locally, follow these steps:

- Clone the repository:
- Install the required dependencies.
- Ensure you have the BRFSS datasets for 2015 and 2021 in CSV format.
## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
The Behavioral Risk Factor Surveillance System (BRFSS) for providing the data.
The developers of the Python libraries used in this project: pandas, numpy, matplotlib, seaborn, scikit-learn.
