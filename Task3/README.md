# Sales Prediction Using Python

## Project Description:
Sales prediction involves forecasting the amount of a product that customers will purchase, taking into account various factors such as:
- Advertising expenditure on different platforms.
- Target audience segmentation.
- Advertising platform selection.

The project utilizes machine learning techniques in Python to analyze and interpret advertising data, enabling businesses to:
- Predict future sales.
- Optimize advertising strategies.
- Maximize sales potential.

---

## Features in the Dataset:
- **TV**: Advertising budget spent on TV (in thousands of dollars).
- **Radio**: Advertising budget spent on Radio (in thousands of dollars).
- **Newspaper**: Advertising budget spent on Newspapers (in thousands of dollars).
- **Sales**: Sales of the product (in thousands of units).

---

## Steps in the Project:

### 1. Data Analysis and Visualization:
- **Exploratory Data Analysis (EDA)**:
  - Pair plots to understand relationships between features and target variable.
  - Correlation heatmap to identify significant predictors of sales.

### 2. Data Preprocessing:
- Split data into:
  - **Features (X)**: `TV`, `Radio`, `Newspaper`.
  - **Target (y)**: `Sales`.
- Split dataset into training and testing sets.

### 3. Model Training:
- Train a **Linear Regression** model using the training data.

### 4. Model Evaluation:
- Evaluate the model using metrics such as:
  - **Mean Squared Error (MSE)**.
  - **R-squared (R2) Score**.

### 5. Sales Prediction:
- Accept user inputs for advertising budgets.
- Predict sales based on user-provided data.

---

