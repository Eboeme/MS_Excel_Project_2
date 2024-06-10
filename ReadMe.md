# Simple dashboard

## About 

This dataset records sales by date, store, salesperson, product, quantity, and price, totalling millions across various items in multiple stores from 1922 to 1924. This dataset was created by me using some specific excel functions.

## Purpose of the project

this project aimed to gain insight into the dataset and create a dashboard in Excel based on the following categories.

## About Data

 Column         |  Description      
:---------------|:-----------------------------------------------------------------------------------------
DATE            | The date column spans across two years.
STORE           | There are 10 stores in the dataset which start from A to J.
SALES PERSON    | The Sales dataset has 12 people spanning various dates.
PRODUCT         | 18 products were being sold in the various stores.
QUANTITY        | The number of goods sold are between the numbers 20 and 100
PRICE           | The price column has to do with random no less than 100,000 naira
TOTAL SALES     | The total sales is simply the price multiplied by the quantity of goods 
	
### Approach used

**Data Wrangling:** This is the first step where data inspection is done to ensure **NULL** values and missing values are detected and data replacement methods are used to replace missing or **NULL** values.

No null values were found in the dataset.

**Sorting**
the dataset was first sorted by the store column from A to Z and was later sorted by Sales person also using alphabetical order.

**Feature Engineering:** This will help us create pivot tables and pivot charts based on the dataset.

1) the first pivot table created made use of date(month) which were placed under the rows and also the total sales column which was placed under the values section in the field list.

2) the second pivot table was created which was based on the product column being placed under the rows and the total sales was placed under the values section of the field list.

3) The third pivot table created was based on the sales made per store. The store column was placed under the rows and the total sales column was placed under the values section of the field list.

4) The fourth pivot table was created which was based on the store column which was placed under the rows section, the salesperson which was placed under the column section and the total sales which were placed under the values section of the field list.

The dashboard created was made up of four slicers and four charts.

the first chart talks about the total sales which were made between JAN TO DEC and from the chart we can see the month of June recorded the most sales.

the pie chart was based on the products being sold and the total sales made per product and also from the chart we can say that Garri was the most purchased item.

the stacked column chart was based on the various stores and their total sales made by salespersons. this means that we had various sections divided into different parts. Store J recorded the most sales as a result of Nico.

The bar chart was based on the stores and the total sales made.

the four slicers used was based on the dataset in four columns. These columns consist of the store, salesperson, products and date.

Various relationship was established between the slicers and the charts.

Based on the dashboard created, we could see that the salesperson called Atiba sold items in six stores which was the highest throughout the data set.

