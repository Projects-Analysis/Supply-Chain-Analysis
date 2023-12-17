# SUPPLY CHAIN ANALYSIS USING PYTHON 

### INTRODUCTION 

###### This project focuses on analyzing data from a cosmetics, haircare, and skincare company to identify trends and insights related to product quality, shipping costs, and distribution. The goal of the project is to provide valuable information to the company that can be used to improve its quality assurance process, reduce shipping costs, and optimize its distribution network.

###### The project involves analyzing a variety of data sources, including sales data, defect data, shipping data, and distribution data. The data is analyzed using statistical methods and visualization techniques to identify trends, patterns, and correlations. The insights and recommendations from the project are presented in a clear and concise manner to make them actionable for the company.

###### The target audience for this project is the management team of the cosmetics, haircare, and skincare company. The insights and recommendations from the project are intended to help the management team make informed decisions about its product quality, shipping costs, and distribution network. 



## Imported Python Libraries for the Analysis 

##### * import pandas as pd
##### * import matplotlib.pyplot as plt
##### * import plotly.express as px
##### * import plotly.io as pio
##### * import plotly.graph_objects as go
##### * pio.templates.default = "plotly_white" 


## Importing the Data into Python 
##### data = pd.read_csv(r"C:\Users\User\supply-chain-data.csv") 

## Checking the First 10 Rows of the Dataset

##### data.head(10) 
![Top 10 Rows](https://github.com/Projects-Analysis/Supply-Chain-Analysis/assets/149543175/b2b7894d-cef6-4327-9b94-b48dc0bf1a5e) 

## Checking the Last 10 Rows of the Dataset 

##### data.tail(10) 
![Last 10 Rows](https://github.com/Projects-Analysis/Supply-Chain-Analysis/assets/149543175/a4dff974-e4c1-4c16-9d88-8cdff82400ee) 

## Checking the Number of Rows and Columns in the Dataset

##### data.shape 
###### (100, 24) 

## Let's have a Look at the Columns Headings 

##### list(data.columns) 
![Columns Headings](https://github.com/Projects-Analysis/Supply-Chain-Analysis/assets/149543175/81b1ff12-0ec0-43b0-a7bc-b7313249a026) 

## Checking the Dataset for Null Values
##### null_values = data.isnull()
​
###### print(null_values)
![Null Values 1](https://github.com/Projects-Analysis/Supply-Chain-Analysis/assets/149543175/9c0e52a0-5b7d-49f7-998a-7a449e77897d)
![Null Values 2](https://github.com/Projects-Analysis/Supply-Chain-Analysis/assets/149543175/9ee02c07-2e7d-45e7-acb7-03a0217db7c9) 

## Let's Check the Number of Duplicates we have in the Dataset
![Duplicates 1](https://github.com/Projects-Analysis/Supply-Chain-Analysis/assets/149543175/6b007e40-9ba0-4732-a6d1-ebc01dfe0374)


## Checking if Duplicates Exist in the Dataset Using Conditional statement
![Duplicates](https://github.com/Projects-Analysis/Supply-Chain-Analysis/assets/149543175/6fa964b1-6eb9-4eb5-80b2-6120e1e75c3f) 

## Let’s have a Look at the Descriptive Statistics of the Dataset
![Descritive Stas](https://github.com/Projects-Analysis/Supply-Chain-Analysis/assets/149543175/e65e0d9a-096c-43ad-a2d3-8d6b94c0121e)

## Let’s get started with Analyzing the Supply Chain by Looking at the Percentage of Sales by Product Category
![Product Category](https://github.com/Projects-Analysis/Supply-Chain-Analysis/assets/149543175/5c9f7ddb-4285-4b52-84d9-86b379c7841a)
![Product Category 2](https://github.com/Projects-Analysis/Supply-Chain-Analysis/assets/149543175/47a3880a-7fc2-4e56-943c-f1175c51e071)
#### The chart above shows that 45% of the sales come from skincare products, 29.5% from haircare, and 25.5% from cosmetics 

## Relationship Between the Price of the Products and the Revenue Generated
![Price and Revenue 1](https://github.com/Projects-Analysis/Supply-Chain-Analysis/assets/149543175/c313d293-149f-4c94-ab93-5ed1a0e31677)
![Price and Revenue 2](https://github.com/Projects-Analysis/Supply-Chain-Analysis/assets/149543175/14d09414-e187-452d-b22a-f82370d81437)
#### The graph shows that skincare products have the highest revenue generated, followed by cosmetics and then haircare. This suggests that skincare products are the most popular and profitable product type. Thus, the company derives more revenue from skincare products and the higher the price of skincare products, the more revenue they generate.
​





