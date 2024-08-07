# Sales-and-Customer-Behavior-Analysis
## What is in this data and how we are solving this
### here is the flow diagram how i'm going to solve
![image](https://github.com/user-attachments/assets/7d976196-9b4d-4c0b-9e56-5cfdd59cb5d7)

## Analysis
![image](https://github.com/user-attachments/assets/b35ed527-cb81-4b35-9879-8e5745d1aa29)


#### These are the problems we are going to tackel   
So, lets understand the data:  
we have one data table which has 8 columns and 10 rowa of data becoz this is sample dataset.  
As we are doing analysis using Pandas we need some libraries to get it done..  

| Libraries|Uses|
|----------|----|
|`import pandas as pd`|pandas|
|`import numpy as np`|Numpy|
|`from sklearn.cluster import KMeans`|for Customer segmention|
|`import matplotlib.pyplot as plt`|Visualize|

> ###  The Company wants to how to boost thier Sales
>  ** this is the main goal of every product selling or B2C Companies.

![image](https://github.com/user-attachments/assets/ee4d8362-0768-4758-a5f6-3163730459b7)
These are the criteria that a company will have,  
based on these we are analysing with the given Problem  
## How we are Analysing!!  
### 1. Understand the concepts
-------------------------------
### Find the Top Selling Product  
![image](https://github.com/user-attachments/assets/fd32bc18-3784-41d3-96b8-a89b5697c3b1)

### Analysing Customer behavior
![image](https://github.com/user-attachments/assets/ec68f40d-ba73-4d11-9e26-e402e09b3f08)

### Inventory Management
![image](https://github.com/user-attachments/assets/22e22928-ec14-4bb9-85f5-02f4ed861082)
-------------------------------

### 2. Perform the Analysis
> `Check the Code`

### 3.Insights From Analysis
-------------------------------
### Customer Segmentation:   
Most customers fall into Segment 0, indicating a lower purchase volume, while only a few customers (C002) make up the highest sales segment (Segment 1).  
### Product Performance:  
Product P002 is the top-selling product, contributing over 40% of the total sales. Focusing marketing efforts on such high-performing products could boost sales.   
Most of the products from P002 are sold in East Region which shows lead in Sales.  
### Sales Trends:  
There is a noticeable peak in sales on specific dates (e.g., 2024-07-05), which could be due to promotions or other events. Identifying these trends helps in planning future sales strategies.
### Revenue  
Among the categories 'Apperal's are the most Procduct Sold and Generated more Revenue its Evident that Product ID P002 is Top Selling product, more sales in East Region and highest revenue generating Product.
### Inventory management
Product P003 has to restock or reload the product as its the one whcih is sold more in Quantity (TotalQuantitySold = 5).  

### 4.Recommendations
>[!Important]
> Need a attentions to the marketing strategies for least sold produdt P003(Under Performing in East and west) regions.  
> Focus on expanding the Electronics product 

## Conclusion
This report highlights the key findings from the sales data analysis, including customer segmentation, product performance, and sales trends, optimization of Invemtory management. These insights can help in making informed business decisions to enhance sales and customer engagement.







