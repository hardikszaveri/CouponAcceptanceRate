Will the Customer Accept the Coupon?

Goal : Use data visualizations and probability distributions skills to distinguish between customers who accepted a driving coupon versus those that did not

Overview

Imagine driving through town and a coupon is delivered to your cell phone for a restaurant near where you are driving. 
Would you accept that coupon and take a short detour to the restaraunt? Would you accept the coupon but use it on a sunbsequent trip? 
Would you ignore the coupon entirely? What if the coupon was for a bar instead of a restaraunt? 
What about a coffee house? Would you accept a bar coupon with a minor passenger in the car? 
What about if it was just you and your partner in the car? Would weather impact the rate of acceptance? What about the time of day?

Obviously, proximity to the business is a factor on whether the coupon is delivered to the driver or not, but what are the factors 
that determine whether a driver accepts the coupon once it is delivered to them? How would you determine whether a driver is likely to accept a coupon?

Data

This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. 
The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. 
Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. 
There are five different types of coupons -- less expensive restaurants (under \$20), coffee houses, carry out & take away, bar, and more expensive restaurants (\$20 - \$50).


Repo Structure

1. The coupon_acceptance_rate.ipynb file contains python code related to data analysis, visualization
2. The data folder has coupons.csv file that contains sample data used in this application
3. The couponacceptanceratereport.docx file has brief report on differences between customers who did and did not accept the coupons.



Key Highlights

1.	There are five distinct types of coupons: Restaurant under 20, Carry-Out & Take Away, Restaurant 20-50, Bar and Coffee House. The Coffee House coupon has highest distribution among all types and its acceptance rate is higher compared to Bar coupon acceptance rate.
2.	The Bar coupon acceptance rate is 40.94% for a given data where customer will use it right away or before it expires.
3.	The highest Bar Coupon Acceptance rate is 76.17% for customers who went to bar three or more times and their acceptance is even higher than overall Bar coupon acceptance rate.
4.	The CoffeeHouse Coupon Acceptance rate is 49.70% for a given data where customer will use coupon right away or before it expires.
5.	The highest CoffeeHouse coupons acceptance rate is 76.63% for customers who go to a CoffeeHouse more than once a month with Friends or Partner and their acceptance is even higher than overall CoffeeHouse coupon acceptance rate.



Next steps and Recommendations

1.	Further analysis of bar coupons data to get an insight on why Bar coupon acceptance rate is lower for customers who visits at-least once but less than three times and identify the parameters (if any) which reduces their acceptance rate.
2.	Further analysis of coffee house coupons data for customers age between 40 and 50 to get an insight of why their coupon rejection rate is higher than their acceptance rate.
3.	Data exploration for Restaurant under 20, Carry-Out & Take Away, Restaurant 20-50 types coupons to get insights on their coupon acceptance rate.




