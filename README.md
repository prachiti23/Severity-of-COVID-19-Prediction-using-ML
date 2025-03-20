# COVID-19 Severity Prediction Using ML

## Overview

This project aims to predict the severity of COVID-19 cases using Machine Learning techniques, specifically Decision Trees and Support Vector Machines (SVM). The model achieves 95.2% accuracy in classifying patient severity.

## Dataset & Preprocessing

* Dataset: Contains COVID-19 patient data with various medical parameters.

* Data Preprocessing Steps:

    * Removed missing values and handled inconsistencies.

    * Applied categorical encoding to transform non-numeric data into numerical format.

    * Used statistical methods (describe(), corr()) to analyze dataset properties.

## Exploratory Data Analysis (EDA)

* Used matplotlib and seaborn for data visualization.

* Explored correlations between different medical features.

## Model Training & Algorithms

* Algorithms Used:

    * Decision Tree Classifier

    * Support Vector Machine (SVM)

* Feature Importance: Although calculated, all feature importance values were close to zero, leading to the use of all features for model training.

* Train-Test Split: Dataset was split into training and testing sets.

## Evaluation Metrics

* Confusion Matrix

* Accuracy Score

* Classification Report (Precision, Recall, F1-score)

## Results

* Achieved a high accuracy of 95.2%.

* Visualized decision trees for better interpretability.

* Identified key patterns in the dataset that contribute to severity prediction.

## Installation & Usage

1. Clone the repository:

2. Install dependencies:

3. Run the Jupyter Notebook or Google Colab to train and test the model.

## Visualization

Decision Tree visualization for interpretability.

Confusion matrix and classification reports for model evaluation
