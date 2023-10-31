##Future Sales Prediction README

This Jupyter Notebook provides a machine learning model for predicting future sales based on historical sales data and various relevant features. The code includes data preprocessing, exploratory data analysis, data cleaning, and model building. Follow the steps below to run this code and make future sales predictions

##Prerequisites

1.Ensure you have Python installed on your system.
2.Install Jupyter Notebook and the required libraries using pip:
'''bash
pip install jupyter numpy pandas scikit-learn matplotlib seaborn
'''

##Steps to Run the Code

1.Clone or download the Jupyter Notebook file and the dataset('future_sales_prediction.csv') to your local machine.
2.Open a terminal and navigate to the directory containing the Jupyter Notebook and the dataset.
3.Start a Jupyter Notebook session:
'''bash
jupyter notebook
'''
4.In the Jupyter Notebook dashboard, open the 'Future_Sales_Prediction.ipynb' file.
5.Run the code cells in the notebook sequentially by clicking on each cell and pressing Shift + Enter.
6.You can interact with the code, view visualizations, and assess model performance metrics as the code executes.
7.The final model, a Random Forest Regressor, is saved as 'sales_prediction_model.pkl' and can be used for making future sales predictions.

##Dataset Used

In this project, we used a future sales prediction dataset obtained from Kaggle.In the context of future sales prediction for a retail company, the dataset encompasses critical information for understanding and forecasting sales performance. A retail company's sales performance is influenced by various elements, including product attributes, market dynamics, and customer interactions. While the dataset contains 04 columns, the focus is on analyzing these factors comprehensively to enhance the accuracy of sales predictions. Accurately predicted sales enable the retail company to optimize inventory, marketing strategies, and resource allocation, leading to increased sales and improved overall performance.
 You can access the dataset on Kaggle at the following URL: [Future Sales Prediction Dataset](https://www.kaggle.com/datasets/chakradharmattapalli/future-sales-prediction).

##About the Dataset

The dataset includes historical sales data and various features that can influence future sales. These features may encompass factors such as time trends, product attributes, pricing, marketing efforts, and external economic conditions. Understanding the relationship between these factors and sales is essential for accurate predictions.

Key features in the dataset may include:

-Date
-Product information
-Price
-Promotion data
-Historical sales
-External factors
-Market trends
We utilized this dataset to build machine learning models for predicting future sales,the code and Jupyter Notebook provide a step-by-step guide on data preprocessing, exploratory data analysis, data cleaning, and model development.

##Understanding the Code

The code consists of the following sections:
-Importing necessary libraries and reading the dataset.
-Data preprocessing, including handling missing data, feature engineering, and time series analysis.
-Exploratory data analysis with visualizations to understand historical sales patterns and influential factors.
-Building and evaluating regression models for future sales prediction:
    -Linear Regression
    -Ada boosting Regression
    -Random Forest Regression (final model)
Saving the trained Random Forest Regressor model for making future sales predictions.

##Data Sources

The dataset used in this code (future sales prediction.csv) is assumed to be available in the same directory as the Jupyter Notebook. This dataset contains sales data and relevant features used for training and evaluating the predictive models.