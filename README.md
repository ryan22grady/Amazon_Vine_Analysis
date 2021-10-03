# Amazon_Vine_Analysis

## Analysis Overview
This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.\
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.\
We focused on the US reviews for video games.

## Resources
- Data Source: [Amazon Review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt), [Video Games Review dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz)
- Software: Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS

## Results
### Total number of reviews
- Vine reviews

![Screen Shot 2021-10-03 at 5 55 28 PM](https://user-images.githubusercontent.com/84995704/135774319-bbf5bf49-82e3-4fe5-9da7-bc9429327f9e.png)

- Non-Vine reviews 

![Screen Shot 2021-10-03 at 5 56 32 PM](https://user-images.githubusercontent.com/84995704/135774331-06821a45-6b0c-4877-a1a1-9aa368d3dcf0.png)


### Total number of 5-star reviews
- Vine reviews 

![Screen Shot 2021-10-03 at 5 57 17 PM](https://user-images.githubusercontent.com/84995704/135774374-e45cf3b2-a5cf-4096-9960-94deaaf0a170.png)

- Non-Vine reviews

![Screen Shot 2021-10-03 at 5 57 48 PM](https://user-images.githubusercontent.com/84995704/135774383-b9d0c2f8-3004-4e29-9be8-3eb13e62b881.png)
