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
5. Summary of Findings:

      #### <ins>General Acceptance</ins>: 
      The overall acceptance rate of coupons across all categories is 56.84%. This suggests a moderate level of acceptance amongst the participants in the study.

      #### <ins>Specific to Bar Coupons</ins>:
      Among those who chose bar coupons, the acceptance rate is 41.00%, which is significantly lower compared to the general acceptance rate.
      ##### Frequency of Bar Visits: 
      Individuals who go to a bar more than three times a month are much more likely to accept bar coupons, with an acceptance rate of 78.00%, compared to   a lower rate of 38.03% among those who visit three or fewer times a month.
      ##### Age Factor: 
      Bar coupon acceptance increases with age among frequent bar-goers, evidenced by a 69.52% acceptance rate among drivers over the age of 25 who go to a bar more than once a month.
      ##### Young Drivers: 
      Young drivers under the age of 30 who frequently visit bars have a relatively high acceptance rate of 72.17%.

      #### <ins>Socio-Demographic influencing Factors</ins>:

      ##### Occupation and Passenger Composition: 
      Drivers who frequent bars more than once a month and have passengers who are not kids and do not work in farming, fishing, or forestry show a       somewhat high acceptance rate of 71.32%.
      ##### Marital Status: 
      Similarly, the acceptance rate remains the same (71.32%) for drivers who are not widowed, suggesting that marital status (in the context of being widowed or not) has no significant effect when other factors are held constant.

      #### <ins>Comparison with Other Activities</ins>:
      Drivers who frequent cheap restaurants more than four times a month with an income less than $50K show a lower bar coupon acceptance rate of 45.35%. This could suggest that economic factors or alternative preferences in leisure activities affect coupon acceptance.


### Conclusion:
#### The findings suggest that the frequency of visiting bars is a significant predictor of bar coupon acceptance, especially among those who frequent bars more than three times a month. Age also plays a role, with higher acceptance noted among older frequent bar-goers.
#### Socio-demographic factors such as occupation, passenger composition, and marital status, provide insightful trends but appear less impactful compared to the frequency of visits and age. 
#### Promotional strategies might be more effective if they are targeted toward frequent, older bar-goers, potentially customized by socio-demographic profiles.

