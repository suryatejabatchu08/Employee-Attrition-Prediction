# Employee Attrition Prediction

Predicting employee attrition is a critical task for human resources (HR) departments. The goal of this project is to develop a machine learning model that identifies employees at risk of leaving the organization. This predictive capability can help reduce turnover rates and HR-related costs by enabling proactive interventions.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Notebook Overview](#notebook-overview)
4. [Technologies Used](#technologies-used)
5. [Setup and Usage](#setup-and-usage)
6. [Project Structure](#project-structure)

---

## Introduction

Employee attrition is a significant challenge for businesses as it increases costs associated with hiring, training, and knowledge transfer. Losing employees also impacts organizational productivity. 

This project aims to:

- Predict whether an employee will leave the organization.
- Identify factors contributing to employee attrition.
- Provide actionable insights to HR teams to improve retention strategies.

**Key Goals:**
- Use the IBM HR Analytics dataset to build a predictive model.
- Perform exploratory data analysis to understand the dataset.
- Train machine learning models and evaluate their performance.
- Use SHAP (SHapley Additive exPlanations) to enhance explainability.

---

## Dataset

The dataset used in this project is **`WA_Fn-UseC_-HR-Employee-Attrition.csv`**, which contains information about employees such as:

- **Demographic information** (e.g., age, education, gender).
- **Work-related features** (e.g., department, job role, monthly income, overtime).
- **Work-life balance** (e.g., years at company, years in current role, stock options).

**Target Variable:**
- `Attrition` (Yes = 1, No = 0): Indicates whether the employee has left the organization.

**Dataset Details:**
- **Rows:** 1,470
- **Columns:** 35

The dataset is publicly available and is commonly used for machine learning projects focused on HR analytics.

---

## Notebook Overview

The notebook [Employee_Attrition.ipynb](https://github.com/suryatejabatchu08/Employee-Attrition-Prediction/blob/main/Employee_Attrition.ipynb) contains the following sections:

1. **Introduction**
   - Overview of the problem statement and project goals.
   
2. **Data Loading**
   - Load the dataset into a DataFrame and display its structure.
   
3. **Exploratory Data Analysis (EDA)**
   - Statistical summaries and visual insights into the data.
   
4. **Data Preprocessing**
   - Handle missing values, encode categorical variables, and scale numerical features.
   
5. **Model Building**
   - Experiment with machine learning algorithms (e.g., Logistic Regression, Random Forest).
   
6. **Model Evaluation**
   - Evaluate model accuracy, precision, recall, and F1-score.
   
7. **Explainability**
   - Use SHAP to interpret model predictions.

The notebook includes clean, modular code, making it easy to adapt and extend.

---

## Technologies Used

This project leverages the following technologies:

- **Languages/Libraries:**
  - Python (NumPy, Pandas, Matplotlib, Seaborn)
  - Scikit-learn
  - SHAP (SHapley Additive exPlanations)

- **Tools:**
  - Jupyter Notebook
  - Google Colab (optional for running the notebook in the cloud)

---

## Setup and Usage

To run this project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/suryatejabatchu08/Employee-Attrition-Prediction.git
   cd Employee-Attrition-Prediction
   ```

2. **Create and activate a virtual environment**:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: `env\Scripts\activate`
   ```

3. **Install the dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the notebook**:
   Open the `Employee_Attrition.ipynb` notebook in Jupyter or your preferred environment and follow the instructions to execute each cell.

---

## Project Structure

```
Employee-Attrition-Prediction/
│
├── Employee_Attrition.ipynb  # Jupyter Notebook with code and analysis
├── WA_Fn-UseC_-HR-Employee-Attrition.csv  # Dataset
└── README.md  # Project documentation
```

---
