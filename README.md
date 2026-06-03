# Cloud-Service-Outage-Severity-Prediction-Using-Machine-Learning
This project implements a machine learning pipeline to predict the severity of cloud service outages based on the CloudOutagesAI dataset.
# Cloud Outage Severity Prediction System

## Project Overview
This project implements a machine learning pipeline to predict the severity of cloud service outages based on the CloudOutagesAI dataset.
## Requirements
- Python 3.x
- Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn

## Project Structure
The code is organized into the following mandatory sections:
1. Pre-processing: Cleaning data, handling missing values (median/mode), and encoding categorical variables.
2. Feature Extraction: Using Random Forest to identify the top 15 predictors and normalizing data with StandardScaler.
3. Data Analysis: Statistical breakdown and class balance verification.
4. Machine Learning Experimentation: Implementation of Logistic Regression, Decision Tree, and Random Forest.
5. Results & Analysis: Performance evaluation using Accuracy, Precision, Recall, and F1-Score.

## How to Run
1. Ensure CloudOutagesAI.csv is in the same directory as the notebook.
2. Run all cells in notebook.ipynb.
3. The model will output accuracy scores and save visualization plots.

## Key Findings
- Best Model: Logistic Regression (99.59% Accuracy).
- Most Important Feature: duration_minutes.
