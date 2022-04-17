# Analysis Overview
This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for Shoes.

## Resources
Data Source: Amazon Review datasets, Shoes Review dataset
Software: Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS
## Results
### Total number of reviews
Vine reviews

<img width="428" alt="Screen Shot 2022-04-17 at 7 42 24 PM" src="https://user-images.githubusercontent.com/96554223/163736431-07a600ef-eef1-4edf-82d1-87cd96237439.png">

Non-Vine reviews

<img width="438" alt="Screen Shot 2022-04-17 at 7 43 24 PM" src="https://user-images.githubusercontent.com/96554223/163736446-c4b946db-35ff-4e89-92cf-a8cb703b7aef.png">

### Total number of 5-star reviews
Vine reviews

<img width="711" alt="Screen Shot 2022-04-17 at 7 44 20 PM" src="https://user-images.githubusercontent.com/96554223/163736474-e53d45a8-436d-4c6c-902b-8dbc00b202f2.png">

Non-Vine reviews

<img width="747" alt="Screen Shot 2022-04-17 at 7 44 46 PM" src="https://user-images.githubusercontent.com/96554223/163736487-86c64f62-a475-435c-a145-791a5c325c04.png">

### Percentage of 5-star reviews
Vine reviews

<img width="710" alt="Screen Shot 2022-04-17 at 7 45 12 PM" src="https://user-images.githubusercontent.com/96554223/163736498-61b2c11f-546e-409a-ad62-9fbe1273034c.png">

Non-Vine reviews

<img width="775" alt="Screen Shot 2022-04-17 at 7 45 38 PM" src="https://user-images.githubusercontent.com/96554223/163736516-bb4463a8-089a-48dc-85c3-079f5c878171.png">

## Summary
59% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 54%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
