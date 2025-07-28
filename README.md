# coupons_accepted
In this first practical application assignment of the program, you will seek to answer the question, “Will a customer accept the coupon?” The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those who did not. 
Coupon Acceptance Analysis Report

OverviewThis report explores customer behavior based on whether they accepted or declined coupons. The dataset includes a variety of demographic, behavioral, and contextual variables. Our objective is to highlight key differences between these two customer groups and visualize trends that can inform marketing strategies.

1. Dataset Summary

Total records: 12,584

Target variable: y (1 = accepted, 0 = not accepted)

Variables: Age, Gender, Income, Coupon Type, Time of Day, Weather, Companion, Destination, etc.

2. Overall Acceptance Rates by Coupon Type

Coupon Type

Acceptance Rate

Carry out & Take away

73.3%

Restaurant(<20)

70.7%

Coffee House

49.9%

Restaurant(20-50)

44.2%

Bar

40.9%

Insight: Low-cost and quick-service food coupons perform best.

3. Demographic Insights

Age: Younger groups (21–30) show higher acceptance. Customers aged 50+ accept coupons the least.

Gender: Slightly higher acceptance among females.

Income: Mid- and lower-income groups ($25K–$62.5K) are most receptive to coupons.

4. Contextual Influences

Time of Day: Afternoon and evening see the highest coupon acceptance.

Weather: Sunny weather leads to higher acceptance; rainy and snowy conditions reduce it.

Passenger Type: People with friends are most likely to accept coupons, while those alone are least likely.

5. Statistical Analysis

Correlation Heatmap (Numeric): Weak correlations overall. Coupon distance negatively correlates with acceptance.

Cramér’s V (Categorical vs y):* **

Strongest association: coupon type (0.26)

Moderate: passanger, destination, time, expiration

Weak: gender, income, education

6. Key Takeaways

Quick, low-cost food offers perform best.

Young, social customers are prime targets.

Afternoon/evening is a strategic time window.

Weather and companionship context affects responsiveness.

Next Steps

Build a simple machine learning model to predict coupon acceptance.

Test targeted strategies on specific demographics (e.g., young professionals).

Repository InfoPublish your Jupyter Notebook, cleaned dataset (optional), and this report on GitHub with a README to showcase findings and visualizations.

Author: [Your Name]Project: Customer Coupon Acceptance AnalysisTools: Python, Pandas, Seaborn, Matplotlib, Plotly
