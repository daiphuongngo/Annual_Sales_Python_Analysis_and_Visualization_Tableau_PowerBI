# Annual_Sales_Analysis_and_Visualization

Dataset: as per my Github
Programming language: Python 
Platform: Google Colab
Analysis methods: Pandas, Matplotlib

## Overview: 
In this repository, we will run a Sales Analysis and Visualization in Python on 200,000 sales data points to come up answers to these Revenue questions.

## Language & Tool:

- Python

- Tableau

## Data Cleaning:
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)

## Data Exploration: 5 highly common questions in business related to the data:
1/ What was the best month for Sales? How much was earned on that month?
2/ Which city had the best Sales of the year?
3/ When was the most efficient time to display ads to maximize/optimize the possibility of customers' decisions to buy products?
4/ Which products were most sold together?
5/ Which product was sold the most? Why do you think it was the best-selling product?

## Data Preparation with different pandas & matplotlib methods:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .transform() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize results
- Labeling graphs

## Evaluation:

December had the highest Sales Value at US$ 4,613,443.5. To dive deeper into why December had the highest Sales Value. We can analyze further by the following hypotheses:
- Holiday season (for example Christmas, New Year, etc.) might affect and have a positive correlation with the highest sales of the year, namely in December.
- Electronics corporations launch new products in Quarter 4 so people tend to spend more in December.

San Francisco had the highest Sales at US$ 8,262,204. This can be explained by some possible reasons:
- Silicon Valley is based in San Francisco.
- There is a density of engineers in San Franciso with high income. Therefore, they tend to spend more in this city, especially on hi-tech products.

The peak of placing Orders was at 11 AM and 12 PM (during lunch break), and at 7 PM, when people got home after work. Therefore, running an ad within 30-60 minutes before these two periods can be recommended to get the most viewers.


The top-selling products were iPhone, Lightning Charging Cable by 882 items sold at the same time within the same order. Companies can sell their products in a combo to push sales for both best sellers and the less common items. Or they can place promotion on a combo while keeping the regular price of their single purchased product to raise demand for buying a combo rather than a single item.

There is a correlation between the Products' Prices and their Volumes. The AA and AAA Batteries had the highest Volumes Ordered while other pricey products had both low quantities and revenues. As we do not have other data of other factors or criteria such as brand quality to research and analyze further, so far that is the sum-up of our conclusion.

