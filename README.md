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
2. The total observations chose to accept the coupon -  56.84%
3. Coupon for cheap restaurants - "Resaurant(<20)" and for "Carry out & Take away" are accepted more than all other coupons.
  
   ![output1](https://github.com/user-attachments/assets/93490c63-301c-412e-82e3-54d166e4a018)

4. Histogram visualization for temperature -
   
   ![output2](https://github.com/user-attachments/assets/2c160787-5ab9-4176-81e7-6cd5763a2c55)
5. Data Analysis - 
The total observations chose to accept the coupon -  56.84%.

The total proportion of bar coupons chose that were accepted - 41.00%.

The Bar coupon acceptance rate for those who went to a bar 3 or fewer times a month: 38.03%.

The Bar coupon acceptance rate for those who went to a bar more than 3 time a month: 78.00%.

The bar coupon acceptance rate by drivers  who go to a bar more than once a month and are over the age of 25 - 69.52%.

The bar coupon acceptance rate by drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry - 71.32%.

The acceptance rate by drivers who go to bars more than once a month, had passengers that were not a kid, and were not widowed -  71.32%.

The acceptance rate by drivers who go to bars more than once a month and are under the age of 30 -  72.17%.

The acceptance rate by drivers who go to cheap restaurants more than 4 times a month and income is less than 50K -  45.35%.

### Conclusion:
#### The findings suggest that the frequency of visiting bars is a significant predictor of bar coupon acceptance, especially among those who frequent bars more than three times a month. Age also plays a role, with higher acceptance noted among older frequent bar-goers.
#### Socio-demographic factors such as occupation, passenger composition, and marital status, provide insightful trends but appear less impactful compared to the frequency of visits and age. 
#### Promotional strategies might be more effective if they are targeted toward frequent, older bar-goers, potentially customized by socio-demographic profiles.

