# Global superstore sales  Analysis
### Table of Content
   - [Project overview](project-overview)
   - [Data source](data-source)
   - [Tools](tools)
   - [Data cleaning and preparations](data-cleaning-and-preparations)
   - [Exploratory data analysis](exploratory-data-analysis)
   - [Data analysis](data-analysis)
   - [Results](results)
   - [Recommendations](recommendations)
   - [Refernces](references)

### Project overview
The major objective of this project is to monitor sales performance and transform it into actionable insights for the business growth and sustainability.
### Data Source
The primary dataset used for this analysis is the 'global superstore sales dataset.csv' file from kaggle
 - [download here](https://www.kaggle.com/datasets/fatihilhan/global-superstore-dataset)
### Tools
  - Microsoft Excel - Data cleaning
  - Power Bi - Data visualization
### Data cleaning and Preparation
In the initial phase of data preparation, i did the following:
1. Data loading and Inspection
2. check and Handle Missing Values
3. Standardize texts
4. Check for duplicates
### Exploratory Data Analysis
Eda seeks to achieve the following:
1. The key metrics of the business
2. The product category generate more revenue
3. The most sold products by revenue
4. The region generating more revenue
5. The top customers generating more revenue

### Data Analysis
     certain dax measures used
             --- 
             average_order_value = DIVIDE(superstore_orders[totalsales],superstore_orders[total_quantity],0)
             average_quantity= average(superstore_orders[quantity])
             ---
### Results
1. A total profit of $1.47m from a total sales of $61.82m
2. The average quantity sold is 3-4 items
3. The average value of each item sold is $346.7
4. The highest sold product category by revenue is technology by $23m
5. The highest sold product by revenue is Apple smart phone full size by $432,254
6. Tom Ashbrook is the customer with the highest sales record with $226,428
7. The region generating the highest revenue is the central region by $14m
### Recommendations
1. The store can organize a loyalty deal to retain its top customers
2. Discount policy can be organized for top regions
3. The store can strategize of technological products for higher profits
### References
Kaggle global superstore sales dataset
