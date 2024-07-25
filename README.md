
# <center><u>Customers Happiness Prediction for Delivery Service</u></center>

## Overview

This project aims to predict customer satisfaction in a delivery service based on survey responses. Using various machine learning techniques, the goal is to determine whether a customer is happy or not based on their feedback. This notebook showcases my ability to handle a real-world business problem, implement machine learning models, and evaluate their performance effectively.

## Business Problem

### Goal

Predict if a customer is happy or not based on their answers to specific survey questions.

### Data Description

The dataset contains the following attributes:

- **Y:** Target attribute indicating customer happiness (0 for unhappy, 1 for happy)
- **X1:** Order was delivered on time
- **X2:** Contents of the order met expectations
- **X3:** Ordered everything desired
- **X4:** Paid a good price for the order
- **X5:** Satisfaction with the courier
- **X6:** App ease of use

Attributes X1 to X6 represent responses ranging from 1 to 5, where smaller numbers indicate less satisfaction and higher numbers indicate more satisfaction.

### Success Metrics

The initial success metric is to achieve an accuracy score of 73% or higher. But after analyzing the business need, I concluded that predicting unhappy customers (Recall 0) will be better for the company since this client category needs to be  forecasted first to take proactive actions to satisfy them.

## Project Highlights

- **Data Preprocessing:** Handling missing values, encoding categorical variables, and feature scaling.
- **Model Training:** Implementation and Comparison of multiple machine learning models to identify the best performer (Decision Tree, RandomForest, Logistic Regression, AdaBoost, XGBoost).
- **Model Emprovement:** : Using multiples techniaues for model improvement GridSearCV, RandomSearchCV, Ensemble learning, Voting techniques and Stacking.
- **Evaluation Metrics:** Calculation of accuracy, precision, recall (including specific labels), and F1-score.
- **Cross-Validation:** Utilization of cross-validation to ensure the robustness of the model.
- **Visualization:** Data visualization to understand the distribution and relationships within the data.
- **Feature selection:** Selecting the most important features (Only important questions for survey) using Recursive Feature Elimination (RFE) .

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/bellapp/dq5aU4G3aakwhO0a.git
   ```
2. Navigate to the project directory:
   ```bash
   cd dq5aU4G3aakwhO0a
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter notebook:
   ```bash
   jupyter notebook Happy_Customer_notebook.ipynb
   ```

## Results and conclusion

The notebook demonstrates the step-by-step approach to solving the problem, from data preprocessing to model evaluation. The best model achieved an accuracy of 85% and a recall (0) of 92%. Detailed performance metrics and visualizations are provided to support the results.

The most important questions to put in the survey are :
  - 'X1': my order was delivered on time
  - 'X2': contents of my order was as I expected
  - 'X5': I am satisfied with my courier

