# EDA

At start there are 48,895 rows and 16 cols in total

## Empty Values
There are four columns with empty values
- last_review           20.56
- reviews_per_month     20.56
- host_name             0.04
- name                  0.03

As we can see that host_name and name are having very little percentage of missing values, we can delete those rows and still retain 99.9 % of data

last_review is missinterpretted as object dtype by pandas, so typecasting it to datetime dtype

last_review and reviews_per_month are having null values in same identical columns

## Outlier Detection
- host_id
- latitude
- longitude
- price
low_cost, budget, permium, luzury

- minimum_nights
cat

- number_of_reviews
categorical columns or we can cap the very extreme outliers to 400

- reviews_per_month
    - 59 is the highest reviwed host per month
    We can cap the reviews which are above 15 to the value 15

- calculated_host_listings_count


## number_of_reviews



