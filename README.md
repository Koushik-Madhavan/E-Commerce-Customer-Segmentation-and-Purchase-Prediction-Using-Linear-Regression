# E-Commerce Customer Segmentation and Purchase Prediction Using Linear Regression

## Project Description
This project focuses on analyzing an **E-Commerce customer database** containing purchases made by over 500 customers over a year. The goal is to use **Linear Regression** to predict the purchases that a new customer will make during the next year based on their first purchase.

## Business Use-case Overview
Customer segmentation divides a customer base into groups with similar characteristics, such as age, gender, interests, and spending habits. By segmenting customers, businesses can tailor marketing efforts to specific groups, optimizing customer value and improving sales conversion rates.

**E-commerce businesses** use this segmentation to:
- Better understand customer preferences
- Deliver personalized marketing
- Enhance sales conversion

Customer segmentation relies on data points such as:
- **Demographics**: age, income, education level
- **Geography**: location-based data
- **Psychographics**: lifestyle, personality
- **Behavioral data**: spending habits, purchase frequency

## Installation
To run this project, you need Python 3.7 and the following libraries:

- **Numpy**
- **Pandas**
- **Matplotlib**
- **Scikit-learn**

Make sure to install **Jupyter Notebook** to execute the code. It’s recommended to use the **Anaconda distribution** for easy installation as it includes all required libraries.

## Data
The dataset contains **customer purchase data** from an **E-Commerce database**. It includes over **500 entries**. You can clone and unzip the **data.csv** file from the repository to use it locally.

### Dataset Features
The dataset contains the following columns:
- **InvoiceNo**: Unique invoice number for each transaction
- **StockCode**: Product code assigned to each product
- **Description**: Product name
- **Quantity**: Quantity of product per transaction
- **InvoiceDate**: Date and time of transaction
- **UnitPrice**: Price per unit of the product
- **CustomerID**: Unique ID assigned to each customer
- **Country**: Country where the customer resides

## How to Run the Project
1. Download and unzip the project folder.
2. Navigate to the project directory in the terminal.
3. Run the following command to open the **Jupyter Notebook**:
   ```bash
   jupyter notebook E-Commerce Customer Segmentation.ipynb
Data Exploration
The dataset includes customers primarily from the UK, Germany, France, Ireland, and Belgium.
You can visualize the distribution of customers by country using maps or word clouds to explore patterns.
Modeling and Analysis
In this project, Linear Regression is used to predict future customer purchases based on their first transaction and spending habits. The model helps identify patterns in customer behavior and forecast future purchases.

Key Features of the Project:
Customer Segmentation: Group customers based on similar purchasing behaviors.
Prediction of Purchases: Use Linear Regression to forecast future purchases.
Evaluation: The model predicts purchases with a 75% accuracy rate, though further improvements can be made by considering seasonal effects and expanding the dataset.
Conclusion
This project demonstrates how Linear Regression can be applied to customer segmentation and purchase prediction. While the model performs well with an accuracy of 75%, further improvements could be made by:

Incorporating seasonal effects.
Expanding the dataset to enhance prediction accuracy.
