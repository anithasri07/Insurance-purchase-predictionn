# Insurance-purchase-predictionn
Logistic regression project to predict insurance purchase likelihood based on age. Includes data preprocessing, model training, and evaluation using Python (pandas, sklearn). Ideal for beginners exploring binary classification and logistic regression concepts.

# Insurance Purchase Prediction using Logistic Regression

This project uses logistic regression to predict whether an individual will purchase insurance based on their age. The dataset, `insurance_data.csv`, contains information about people's ages and whether they purchased insurance.

---

## Overview
The dataset contains two key columns:
- **Age:** Age of the individual.
- **Purchased Insurance:** A binary value (0 or 1) indicating if the individual purchased insurance.

The objective is to build a logistic regression model to predict the likelihood of insurance purchase given the age of an individual.

---

## Features
- **Age:** Age of the individual (independent variable).
- **Purchased Insurance:** Binary value representing the insurance purchase status (dependent variable).

---

## Technologies Used
- **Python**: Programming language.
- **pandas**: For data manipulation and preprocessing.
- **scikit-learn**: For building and evaluating the logistic regression model.

---

## How It Works
1. **Data Preprocessing**:
   - Load the dataset using `pandas`.
   - Split the data into features (`Age`) and target (`Purchased Insurance`).
   - Divide the data into training and test sets.

2. **Model Building**:
   - Use scikit-learn's `LogisticRegression` class.
   - Train the model using the training data.
   - Predict the insurance purchase likelihood on the test data.

3. **Evaluation**:
   - Compare predicted results with actual results from the test set.
   - Metrics such as accuracy, precision, recall, and F1-score can be used for evaluation.

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/insurance-purchase-prediction.git

