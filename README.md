# Amazon_Vine_Analysis

## Overview
The Amazon Reviews for Video Games dataset is analysed in this project to determine if there is a bias toward favorable reviews from the Vine members.
This analysis uses PySpark in the Google Colab Notebook to perform the ETL process to perform the extraction of the dataset, transformation of the data, connection to an AWS RDS instance, and finally loading the transformed data into pgAdmin measuring different statistics for analysis.

## Resources Used
<li>Data Source used: Amazon Review Dataset - Video Games Review</li>
<li>Software Tools used: PostgreSQL 11.9, pgAdmin 4, AWS RDS, GoogleColab Notebook</li>

## Analysis & Result

### Total number of Reviews
1. Vine Reviews
![total n1](https://user-images.githubusercontent.com/86158802/138028707-322ba96c-27cb-4370-820a-4d5f2abc08d0.PNG)

2. Non-Vine Reviews
![unpaid-total](https://user-images.githubusercontent.com/86158802/138028755-01a5b0ef-6bde-46df-a6d8-1b7614e1b875.PNG)

### Total number of 5-star reviews
1. Vine reviews
![paid-5](https://user-images.githubusercontent.com/86158802/138028785-493d9418-73d4-4e5a-84e8-9da700c4d4dc.PNG)

2. Non-Vine reviews
![unpaid-5](https://user-images.githubusercontent.com/86158802/138028801-db0a5cca-1319-436f-83c5-e88b2ad93ef0.PNG)

### Percentage of 5-star reviews
1. Vine reviews
![5-perc](https://user-images.githubusercontent.com/86158802/138028842-0640a654-2203-49b9-ba8a-32f793f2bf9c.PNG)

2. Non-Vine reviews
![unpaid-perc](https://user-images.githubusercontent.com/86158802/138028863-1ca120a2-1beb-46ee-9a5b-8ce8d539d0c8.PNG)

## Summary
There is 51% of the reviews in the Vine program which were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This is a depiction of a bias for the reviews in the Vine program.
