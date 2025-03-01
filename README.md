# E-Commerce-Customer-Segmentation-and-Purchase-Prediction-Using-Linear-Regression

Description
This project focuses on the analysis of an E-Commerce customer database that lists purchases made by over 500 customers over a period of one year. The model developed in this project uses Linear Regression to anticipate the purchases that will be made by a new customer during the following year, based on their first purchase.

Business Use-case Overview
Customer segmentation involves dividing a customer base into groups of individuals with similar characteristics, such as age, gender, interests, and spending habits. The goal is to tailor marketing efforts to specific groups to maximize customer value.

E-commerce businesses use customer segmentation to better understand customers' preferences, allowing them to deliver personalized marketing and improve sales conversion rates.

Customer segmentation relies on data points such as:

Demographics: age, income, education level
Geography: location-based data
Psychographics: lifestyle, personality
Behavioral data: spending habits, frequency of purchase
Install
This project requires Python 3.7 and the following Python libraries:

Numpy
Pandas
Matplotlib
Scikit-learn
Make sure to install Jupyter Notebook to run the code.

It is recommended to use the Anaconda distribution to install Python, as it includes all the required packages.

Data
The dataset includes customer purchase data collected from an E-Commerce database with over 500 entries. You can clone and unzip the data.csv file from the repository to use it locally.

Features
The dataset contains the following columns:

InvoiceNo: Invoice number, uniquely assigned to each transaction.
StockCode: Product code, uniquely assigned to each product.
Description: Product name.
Quantity: Quantity of each product per transaction.
InvoiceDate: Date and time of the transaction.
UnitPrice: Price per unit of the product.
CustomerID: Customer ID, uniquely assigned to each customer.
Country: Country where the customer resides.
Code
The project template is provided in the E-Commerce Customer Segmentation.ipynb notebook. Use this notebook along with the data.csv dataset to complete the project.

To run the notebook:

Navigate to the project directory and run the following commands:
bash
Copy
Edit
jupyter notebook E-Commerce Customer Segmentation.ipynb
This will open the notebook in your browser.

Data Exploration
The dataset is dominated by purchases from the UK, Germany, France, Ireland, and Belgium.
You can visualize the distribution of customers by country using maps or word clouds.
Classifiers
In this project, Linear Regression is used to predict customer purchase behavior based on their first transaction and spending habits. This helps forecast future purchases by identifying patterns in the data.

Conclusion
The project demonstrates customer segmentation using Linear Regression to predict future purchases. Although the model performs well, correctly classifying 75% of customers, improvements can be made by considering seasonal effects and extending the dataset for more accurate predictions.

