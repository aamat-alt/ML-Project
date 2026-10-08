# ML-Project
Introduction to Machine Learning semester project. A 5-part pipeline taking a real-world dataset through the complete machine learning lifecycle.
# Telecom Customer Churn Prediction Pipeline

## Project Overview
This repository contains a semester-long machine learning project focused on predicting customer churn in the telecommunications industry. The goal is to identify customers who are highly likely to cancel their service, allowing companies to proactively offer retention incentives. The project approaches this as a binary classification problem (Churn: Yes/No).

## Dataset
The project utilizes the **IBM Telco Customer Churn** dataset sourced from Kaggle. 
* **Size:** 7,043 rows
* **Features:** A mix of numeric (e.g., `tenure`, `MonthlyCharges`) and categorical variables (e.g., `Contract`, `PaymentMethod`).
* **Target Variable:** `Churn` (Binary: Yes/No)

## Technologies Used
* **Language:** Python
* **Data Manipulation:** pandas, NumPy
* **Visualization:** matplotlib, seaborn
* **Machine Learning:** scikit-learn (`Pipeline`, `ColumnTransformer`, `OneHotEncoder`, `StandardScaler`)

## Project Roadmap
This project is being developed in phases throughout the semester:

* [x] **Part 1: Exploratory Data Analysis (EDA) & Preprocessing Pipeline**
  * Visualized target variable distribution and feature relationships.
  * Engineered a robust, leakage-free preprocessing pipeline using scikit-learn's `ColumnTransformer`.
  * Applied `StandardScaler` for numeric features and `OneHotEncoder` for categorical variables.
  * Handled missing values systematically (`SimpleImputer`).
* [ ] **Part 2: Baseline Model Training & Evaluation** (Upcoming)
* [ ] **Part 3: Advanced Ensembles & Hyperparameter Tuning** (Upcoming)
* [ ] **Part 4: Neural Networks & Model Fairness/Interpretability** (Upcoming)

## Repository Structure
* `Part1_Pipeline.ipynb`: Jupyter Notebook containing the initial Exploratory Data Analysis (EDA) and the leakage-free data preprocessing pipeline.

## How to Run
1. Clone this repository: `git clone https://github.com/aamat-alt/ML-Project.git`
2. Ensure you have Python installed along with the required libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`).
3. Open `Part1_Pipeline.ipynb` in Jupyter Notebook or Google Colab to view the EDA and preprocessing code.
