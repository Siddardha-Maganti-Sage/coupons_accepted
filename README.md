# Coupon Acceptance Analysis Report

Overview: 

This report examines customer behavior based on their acceptance or decline of coupons. The dataset comprises various demographic, behavioral, and contextual variables.

1. Dataset Summary

   Data set used: https://github.com/Siddardha-Maganti-Sage/coupons_accepted/blob/main/coupons_acceptance/data/coupons.csv
   
   Jupiter Notebook link: https://github.com/Siddardha-Maganti-Sage/coupons_accepted/blob/main/coupons_acceptance/prompt_assignment.ipynb
   
   Total records: 12,584
   
   Target variable: y (1 = accepted, 0 = not accepted)
   
   Variables: Age, Gender, Income, Coupon Type, Time of Day, Weather, Companion, Destination, etc.

2. Data Cleanup

   Cleaned up the Car Column since it was missing data.
   Filled in the missing information with the mode 
   Converted string columns to numerical data
   Converted all columns to lowercase for ease of use.
   

3. Overall Acceptance Rates by Coupon Type

   Coupon Type               Acceptance Rate
   
   Carry out & Take away   -   73.3%
   
   Restaurant(<20)         -   70.7%
   
   Coffee House            -   49.9%
   
   Restaurant(20-50)       -   44.2%
   
   Bar                     -   40.9%


4. Demographic Insights

   Age: The younger age group, <30, has a higher acceptance rate.
   
   Gender: Slightly higher acceptance among females.
   
   Income: The income range of low to medium, 25K-62.5K, has the highest acceptance rate.

5. Contextual Influences

   Time of Day: Afternoon and evening (i.e., 2 PM, 6 PM, and 10 PM) see the highest coupon acceptance.
   
   Weather: Sunny weather leads to a higher acceptance rate compared to snow and rainy conditions
   
   Passenger Type: People with friends have accepted coupons the most.
        
6. Statistical Analysis

   Correlation Heatmap (Numeric): No significant correlation was found between numerical points.
   Coupon distance negatively correlates with acceptance.
  

7. Key Takeaways

   Found the Carry out & Take Away, Restaurant (<20) has the highest acceptance rate. This reinforces the notion that low-cost and fast food coupons are most effective.
   
   The younger age group <30 has a higher acceptance rate.
   
   Occupations of Students, the Unemployed, and computer and mathematical professionals have a high acceptance rate.
   
   People with friends have accepted coupons the most.
   
   Sunny weather leads to a higher acceptance rate compared to snow and rainy conditions
   
   The income range of low and medium  25𝐾− 62.5K, has the highest acceptance rate.
   
   Coupon distance negatively correlates with acceptance.

8. Next Steps

   Build a simple machine learning model to predict coupon acceptance.
   
   Test targeted strategies on specific demographics (e.g., young professionals).

Author: Siddardha Maganti

Project: Customer Coupon Acceptance 
Analysis Tools: Python, Pandas, Seaborn, Matplotlib, Plotly
