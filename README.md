# Cloud-Service-Outage-Severity-Prediction-Using-Machine-Learning

This project implements a machine learning pipeline to predict the severity of cloud service outages based on the CloudOutagesAI dataset. The project is designed to run on **Google Colab** for easy execution and reproducibility.

---

## Cloud Outage Severity Prediction System

### Project Overview

This project implements a machine learning pipeline to predict the severity of cloud service outages based on the CloudOutagesAI dataset. All experiments and analysis are performed using a **Google Colab notebook**.

---

## Requirements

* Python 3.x
* Pandas
* Numpy
* Scikit-learn
* Matplotlib
* Seaborn
* Google Colab (recommended)

---

## Project Structure

The code is organized into the following mandatory sections:

* **Pre-processing:** Cleaning data, handling missing values (median/mode), and encoding categorical variables.
* **Feature Extraction:** Using Random Forest to identify the top 15 predictors and normalizing data with StandardScaler.
* **Data Analysis:** Statistical breakdown and class balance verification.
* **Machine Learning Experimentation:** Implementation of Logistic Regression, Decision Tree, and Random Forest.
* **Results & Analysis:** Performance evaluation using Accuracy, Precision, Recall, and F1-Score.

---

## How to Run

1. Open the notebook in **Google Colab**
2. Upload the dataset file:

   ```
   CloudOutagesAI.csv
   ```
3. Run all cells in `notebook.ipynb`

The model will output accuracy scores and generate visualization plots.

---

## Key Findings

* **Best Model:** Logistic Regression (99.59% Accuracy)
* **Most Important Feature:** `duration_minutes`

