# DevelopersHub-AIML-Internship Task 3

## Heart Disease Prediction

### Project Overview
This project is part of the AI/ML Engineering Internship at DevelopersHub Corporation. It focuses on predicting whether a patient has heart disease based on various medical attributes using Machine Learning classification techniques.

### DataSet
**UCI Heart Disease Dataset**
* The dataset contains historical health records of **1,025 patients** and **14 health features** (such as age, sex, chest pain type, cholesterol, blood pressure, etc.).
* **Target Variable:** Binary classification (`1` = Has Heart Disease, `0` = No Heart Disease).
* **Data Quality:** Checked for missing values—the dataset contains **0 missing entries**, making it completely clean.
* **Class Balance:** * Patients with Heart Disease (`1`): **526**
  * Patients without Heart Disease (`0`): **499**

### Tools Used
* Python
* Pandas & Numpy (Data Manipulation)
* Seaborn & Matplotlib (Exploratory Data Analysis & Visualization)
* scikit-learn (Machine Learning & Evaluation Metrics)

### Machine Learning Model
* **Logistic Regression** (with StandardScaler feature scaling)

### Visualizations
* **Age Distribution Plot:** A histogram showing the age spread of the patients.
* **Correlation Heatmap:** A visual matrix showing how different health features correlate with each other and the target.
* **Confusion Matrix:** To track True Positives, True Negatives, False Positives, and False Negatives.
* **ROC Curve:** A graph evaluating the True Positive Rate vs False Positive Rate.

### Summary of Findings
* **Model Performance:** The Logistic Regression model achieved an overall accuracy of **79.51%**.
* **ROC-AUC Performance:** The ROC curve demonstrates strong predictive power, proving the model is effective at distinguishing between healthy and diseased states.
* **Feature Engineering:** Scaling features using `StandardScaler` helped improve gradient convergence and overall model reliability.
