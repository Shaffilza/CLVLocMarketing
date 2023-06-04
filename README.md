# CLVLocMarketing

>This project is designed to serve as an educational resource, created with the specific intention of fulfilling project assignment requirements. Through this endeavor, we aim to explore and apply various concepts and techniques learned in our educational journey.

## Project Tittle: Location-based Marketing for High-Value Customers with Predictive CLV



Customer Lifetime Value (CLV or CLTV) is a metric that represents the total net profit a company can expect to generate from a customer throughout their entire relationship. It takes into account the customer's initial purchase, repeat purchases, and the average duration of their relationship with the company.

RFM and k-means clustering have been used to improve key performance indices, such as increased active customers, total purchase volume, and total consumption amount. Pareto/NBD and Gamma-Gamma models have been used to predict customer lifetime value and customer transaction behavior, helping businesses better understand their customer base. By combining the insights from these models, businesses can optimize their marketing strategies, allocate resources more effectively, and improve overall business performance.

## Problem Statement

This project aims to address three key challenges in location-based marketing for high-value customers with predictive customer lifetime value (CLV):

* Identifying relevant attributes in customer transactional data for accurate CLV forecasting and hotspot area identification.
* Anticipating hotspot regions for high-value clients using CLV estimates.
* Developing a machine learning algorithm with high precision for CLV prediction.

Successful resolution of these challenges will enable enterprises to effectively forecast CLV, segment customers into targeted regions, and design informed marketing and customer engagement strategies.

## Objective Study

* Identify attributes or features that affect the customer lifetime value based on the location. 

* Develop machine learning models by utilizing the identified features to predict Location-based Marketing for High-Value Customers. 

* Evaluate the performance of predictive models


## Installation
Project is created with:
* Python 3.9.7

```
$ pip install lifetimes
$ pip install scikit-learn
$ pip install folium

```
## Start
To run this project, first download the file from the link given in [Data Source](#data-source).
Then download [here](https://github.com/Shaffilza/CLVLocMarketing/blob/main/CLVLocMarketing.ipynb). Install necessary packages. 

## Data Source

The dataset was originally sourced from the UCI Machine Learning Repository and can be found at  https://archive.ics.uci.edu/ml/datasets/online+retail. This dataset consist of 1067371 rows and 8 attributes features. 

Attributes    | Description
------------- | -------------
InvoiceNo	| Unique identifier for each transaction.
StockCode	| Unique identifier for each product.
Description	| Description of the product.
Quantity	| Number of items purchased.
InvoiceDate	| Date and time of the transaction.
UnitPrice	| Price of each item in British pounds.
CustomerID	| Unique identifier for each customer.
Country	| Country where the customer resides.

## Model used & Evaluation Metrics

Pareto | Gamma-Gamma | Kmeans
------------- | -------------| -------------
Mean Squared Error (MSE) | Mean Squared Error (MSE) | Inertia (SSE)
Root Mean Squared Error (RMSE) | Root Mean Squared Error (RMSE)  | Silhouette Coefficient
R-squared |R-squared | Calinski-Harabasz Index
N/A | N/A | Davies-Bouldin Index

 
### Credits

 

 

 



