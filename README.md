# Home Sales

## Description
This project focuses on utilizing SparkSQL to extract vital metrics from home sales data. The primary objectives include creating temporary views, partitioning data, caching and uncaching a temporary table. 

The ultimate goal is to ensure optimized data operations and improved performance.

## Technologies Used
- SparkSQL
- PySpark

## Data Source
https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.2/22-big-data/home_sales_revised.csv

![Getting Started](images/data.png)

## Instructions
Run 'Home_Sales.ipynb' notebook in Google Colab (https://colab.research.google.com/).

May require updating spark_version.

## Data Analysis and Runtime Optimization Steps
Spark was used to 
- create temporary views, 
- partition the data, 
- cache and uncache a temporary table, and 
- verify that the table has been uncached.

The runtime to run a query using cached, uncached and partitioned data was measure. 

### Examples of the questions answered:

- What is the average price for a four-bedroom house sold for each year?

Highest annual average price for a four-bedroom house sold for the period 2019-2022 is showing in 2021.

![Getting Started](images/4bed_avg.png)

- What is the average price of a home for each year it was built that has three bedrooms and three bathrooms?

3 bedrooms and 3 bathrooms homes with the highest average price were built in 2013, and the lowest in 2015.
THe average price for houses in this group that were built in 2010 is on par with the ones built in 2017.

![Getting Started](images/year_built_avg.png)

- What is the "view" rating for homes costing more than or equal to $350,000?

The highest average price for homes in the selected price range has group with view rating 91.

![Getting Started](images/view.png)

## Conclusion

    