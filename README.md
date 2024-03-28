# CODSOFT-SALES-PREDICTION
# Sales Prediction using Machine Learning in Python

Sales prediction involves forecasting the amount of a product that customers will purchase, taking into account various factors such as advertising expenditure, target audience segmentation, and advertising platform selection. In businesses that offer products or services, the role of a Data Scientist is crucial for predicting future sales. They utilize machine learning techniques in Python to analyze and interpret data, allowing them to make informed decisions regarding advertising costs. By leveraging these predictions, businesses can optimize their advertising strategies and maximize sales potential. Let's embark on the journey of sales prediction using machine learning in Python.

## Introduction

This repository contains Python code for predicting sales based on advertising expenditures. It includes data preprocessing, exploratory data analysis, model training, evaluation, and interpretation.

## How to Use

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/ouyale/CODSOFT-SALES-PREDICTION
    ```

2. **Navigate to the Repository:**
    ```bash
    CODSOFT-SALES-PREDICTION
    ```

3. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

5. **Explore the Notebook:**
    Open the `sales_prediction.ipynb` notebook and follow the instructions to run each cell.

## Repository Structure

- `sales_prediction.ipynb`: Jupyter Notebook containing the Python code for sales prediction.
- `advertising.csv`: Dataset containing advertising expenditures and sales data.
- `requirements.txt`: List of Python dependencies required to run the notebook.

## Evaluation Results

After training and testing the machine learning model for sales prediction, I evaluated its performance using the following evaluation metrics:

### Mean Squared Error (MSE)

The Mean Squared Error (MSE) measures the average squared difference between the predicted values and the actual values. A lower MSE indicates that the model's predictions are closer to the actual values, which is desirable. In our case, the MSE was calculated to be 2.416.

### R-squared (R²)

The R-squared value, also known as the coefficient of determination, measures the proportion of the variance in the target variable (sales) that is explained by the independent variables (TV, radio, newspaper advertising expenditures) in the model. R-squared ranges from 0 to 1, where 1 indicates a perfect fit. In our case, the R-squared value was calculated to be 0.913, indicating that approximately 91.3% of the variance in toy sales is explained by the advertising expenditures included in the model.

These evaluation metrics provide insights into how well the model performs in predicting sales based on advertising expenditures. A lower MSE and a higher R-squared value suggest that the model has better predictive performance.

It's important to note that while these evaluation metrics provide valuable information, they should be interpreted in conjunction with other factors such as domain knowledge and business context to assess the overall effectiveness of the model.

## Requirements

- numpy==1.21.2
- pandas==1.3.3
- scikit-learn==0.24.2
- matplotlib==3.4.3
- seaborn==0.11.2
