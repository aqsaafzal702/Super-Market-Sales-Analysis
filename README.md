# Super-Market-Sales-Analysis

## Project Overview
A detailed analysis of historical sales data from three different supermarket branches over a three-month period. The project involves data cleaning, exploratory data analysis (EDA), hypothesis testing, and visualization to uncover insights into sales performance, customer behavior, and pricing strategies.

## Dataset
- **Source**: [Kaggle](https://www.kaggle.com/datasets)
- **Description**: Historical sales data from three supermarket branches, including attributes such as invoice ID, branch, city, customer type, gender, product line, unit price, quantity, tax, total, date, time, payment, COGS, gross margin percentage, and gross income.
 
## Objectives
1. Data Analysis and Cleaning
2. Exploratory Data Analysis (EDA)
3. Research Questions
4. Hypothesis Testing
5. Predictive Analysis

## Data Analysis and Cleaning
- Handled missing values and outliers.
- Preprocessed data for analysis.

## Exploratory Data Analysis (EDA)
- Created various visualizations to understand data patterns and trends.

## Research Questions
- What is the relationship between customer ratings and total sales?
- What is the relationship between product price and quantity sold?

## Hypothesis Testing
- Conducted hypothesis testing to assess differences in customer purchasing behavior.

## Predictive Analysis
### Objective
The goal of the predictive analysis is to forecast customer spending at a supermarket using a linear regression model. This analysis helps in understanding the impact of factors such as branch, city, customer type, gender, product line, unit price, and quantity purchased on total spending.

### Model
- **Linear Regression**: Used for modeling the relationship between independent variables (features) and the dependent variable (total spending).

### Implementation
1. **Feature Selection**: Included features such as branch, city, customer type, gender, product line, unit price, and quantity.
2. **Encoding**: Applied One-Hot Encoding to convert categorical variables into numerical format.
3. **Data Splitting**: Divided the data into training and testing sets.
4. **Training**: Trained the linear regression model using the training data.

### Model Performance
- **Mean Squared Error (MSE)**: 6380.16
- **R² Score**: 0.9019
  - The R² score indicates that approximately 90.19% of the variance in total spending is explained by the model, reflecting a strong fit.

### Visualization
- **Actual vs. Predicted Spending**: Created a scatter plot to visualize the relationship between actual and predicted spending.

## Usage
1. Clone this repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Run the analysis script or Jupyter Notebook.

## Installation
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Scipy
- Scikit-learn
