# ML & AI - Module 5

# Practical Application Assignment 5.1 - Will the Customer Accept the Coupon?
The goal of this project was to use visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not. The dataset used in the analysis is available here:

Data  -  https://github.com/Vanitagarg-school/ML_AI_project1/blob/main/coupons.csv

Jupyter Notebook - https://github.com/Vanitagarg-school/ML_AI_project1/blob/main/Project1%20_coupons.ipynb

Data Analysis:

1. Investigating the data -
The 'Car' metric has over 99% of its values missing, so it is not contributing much value. Therefore, it would be better to drop this metric from further analysis.
Other metrics such as 'Bar', 'CoffeeHouse', 'CarryAway', 'RestaurantLessThan20', and 'Restaurant20To50' have 2% missing values.
Inspect the values to see which responses are most common in the surveys, and consider filling the missing values using the most frequent response as the default.
