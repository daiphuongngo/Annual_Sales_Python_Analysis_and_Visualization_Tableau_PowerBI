# Annual_Sales_Analysis_and_Visualization

## Category:

- Retail

- Electronics

- Sales

## Languages and Tools: 

- Python 

- Power BI

- Tableau

## Platform: 

- Google Colab

## Analysis methods: 

- Pandas

- Matplotlib

## Overview: 

In this repository, I will run a Sales Analysis and Visualization in Python on 200,000 sales data points to come up answers to these Revenue questions.

This project was used for my training when working as a Data Analyst Intern at Center of Talent in AI using Python, Power BI, Tableau in 2020.

## Dataset: 

12 CSV files for 12 months of Sales data in 2019 with the same columns as per my Github's folder

| Order ID | Product | Quantity Ordered | Price Each | Order Date | Purchase Address | 
|-|-|-|-|-|-|

## Language & Tool:

- Python

- Tableau

- Power BI

## Target Achievements:

- Visualized & compared results between charts in Tableau & Power BI to determine that the variables which caused the highest Sales Value as per hypotheses: 

+ December at US$ 4.6 million due to holiday season with more promotions & newly launched products by electronics corporations in Quarter 4, 

+ San Francisco at US$ 8.2 million as Silicon Valley is based there having a density of engineers in San Francisco with high income & spending on hi-tech products, 

+ Peak hours placing orders at 11 AM & 12 PM (during lunch break) & at 7 PM after work, 

+ Top sold products: iPhone, Lightning Charging Cable by 882 items ordered at the same time within the same order (suggested strategy: selling a combo of best sellers & less common items), 

+ The correlation between Prices & Volumes as AA &  AAA Batteries had the highest volumes ordered while other pricey products had both low.

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

## Evaluation + Visualization on Tableau & Power BI:

### Monthly Sales Revenue:

December had the highest Sales Value at US$ 4,613,443.5. To dive deeper into why December had the highest Sales Value. We can analyze further by the following hypotheses:
- Holiday season (for example Christmas, New Year, etc.) might affect and have a positive correlation with the highest sales of the year, namely in December.
- Electronics corporations launch new products in Quarter 4 so people tend to spend more in December.

![Monthly Sales Revenue](https://user-images.githubusercontent.com/70437668/138407880-8ea4baa1-391f-4bda-b097-b6389eaf9373.jpg)

![Monthly Sales Revenue](https://user-images.githubusercontent.com/70437668/138536531-b868be00-91b2-4beb-aaa5-2e4501da1124.jpg)

### City Sales Revenue:

San Francisco had the highest Sales at US$ 8,262,204. This can be explained by some possible reasons:
- Silicon Valley is based in San Francisco.
- There is a density of engineers in San Franciso with high income. Therefore, they tend to spend more in this city, especially on hi-tech products.

![City Sales Revenue](https://user-images.githubusercontent.com/70437668/138407848-a3714843-0cdb-4caf-8d01-56f6723e8783.jpg)

![City Sales Revenue](https://user-images.githubusercontent.com/70437668/138536533-55620432-18fd-4d57-ace3-020614fe73e3.jpg)

The peak of placing Orders was at 11 AM and 12 PM (during lunch break), and at 7 PM, when people got home after work. Therefore, running an ad within 30-60 minutes before these two periods can be recommended to get the most viewers.

### Hourly Sales Revenue:

![Hourly Sales Revenue](https://user-images.githubusercontent.com/70437668/138407897-70337ad5-a4bd-4b08-8f85-289137526390.jpg)

![Hourly Sales Revenue](https://user-images.githubusercontent.com/70437668/138536563-d9839a95-d0d7-4b75-bc90-ce51d882a88b.jpg)

The top-selling products were iPhone, Lightning Charging Cable by 882 items sold at the same time within the same order. Companies can sell their products in a combo to push sales for both best sellers and the less common items. Or they can place promotion on a combo while keeping the regular price of their single purchased product to raise demand for buying a combo rather than a single item.

### Quantity Ordered by Product:

There are seasonal fluctuations which show constant drops from Apr to Aug for almost all products in general. Another lowest decline happened in December after a peak in November. The reasons might be because customers tend to spend for products on or before Thanksgiving in October/November and Chirstmans Sales in December. Then we could spend less on products in December but other priorities such as clothing, food and berage.

A suggestion might be that we can offer some seasonal rapid promotions for some products in summer so customers can spend for some products like batteries, dryers and headphones to solve the low quantities sold during those months. 

Seasonality refers to a pattern of fluctuations above or below some average level that repeats at regular intervals. These “seasons” are viewed as short term patterns.

![Quantity Ordered by Product](https://user-images.githubusercontent.com/70437668/138407928-7e718903-bd88-47db-a02e-5561266df826.jpg)

There is a correlation between the Products' Prices and their Volumes. The AA and AAA Batteries had the highest Volumes Ordered while other pricey products had both low quantities and revenues. Easily-replaceable and affordableproducts like batteries, cables, headphones had more Quantities Sold than other long-used and expensive products like Smartphones, TVs, Laptops, Monitors and Dryers.

As I do not have other data of other factors or criteria such as brand quality to research and analyze further, so far that is the sum-up of our conclusion.

![Quantity Ordered by Product](https://user-images.githubusercontent.com/70437668/138536541-21ad08be-924e-419d-88b2-79b21f484a78.jpg)

### Dashboard - Hourly Sales Revenue and Quantity Ordered by Product:

![Dashboard - Hourly Sales Revenue and Quantity Ordered by Product](https://user-images.githubusercontent.com/70437668/138407971-72e7c621-d985-45ea-b14c-10d51a1cb0fc.jpg)

### Dashboard - Sales Revenue by City, Month:

![Dashboard - Sales Revenue by City, Month](https://user-images.githubusercontent.com/70437668/138407981-5f467fc0-0edc-45ae-8b8d-00253b834bfb.jpg)

### Dashboard - Sales Revenue by Hour, Month, City:

![Dashboard - Sales Revenue by Hour, Month, City](https://user-images.githubusercontent.com/70437668/138407992-cf7f0826-b43f-4547-ab6a-5fa35bc9e742.jpg)

