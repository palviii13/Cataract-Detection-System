# Cataract Risk Prediction

This project aims to predict the risk of cataracts using various machine learning techniques. The project includes data preprocessing, exploratory data analysis, and training different machine learning models to classify the risk of cataracts.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Data Preprocessing and Visualization](#data-preprocessing-and-visualization)
- [Results](#results)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cataract-risk-prediction.git
   cd cataract-risk-prediction

## Usage

1. Mount your Google Drive to access the dataset:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
2. Run the Jupyter Notebook to preprocess the data, perform exploratory analysis, and train the models.

## Model Architecture

### Logistic Regression
- Implements a logistic regression model to classify the risk of cataracts.
- Trains the model using the training dataset and evaluates it using accuracy and recall metrics.

### K-Nearest Neighbors (KNN)
- Implements a KNN classifier to predict cataract risk.
- Evaluates the model using confusion matrix and accuracy metrics.

### Random Forest
- Implements a Random Forest regressor to predict cataract risk.
- Uses the regressor's predict method and rounds the predictions to classify the risk.
- Evaluates the model using confusion matrix and accuracy metrics.

## Data Preprocessing and Visualization

- **Data Preprocessing:** Checks for missing values, encodes categorical variables, and normalizes numerical features.
- **Exploratory Data Analysis:** Visualizes relationships between variables using correlation matrices and count plots.

## Results

- **Logistic Regression Accuracy:** 92.06
- **KNN Classifier Accuracy:** 93.43
- **Random Forest Accuracy:** 94.24


   
