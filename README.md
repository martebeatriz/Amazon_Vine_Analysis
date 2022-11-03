# Amazon_Vine_Analysis

## Overview of the analysis:
Using my knowledge of the cloud ETL process, created an AWS RDS database with tables in pgAdmin. The dataset contained toy reviews from Amazon Review datasets. 

My analysis explored the possibility of bias in reviews written as part of the paid Vine review program.<br>

Technologies used: PySpark, Pandas, and SQL.


## Results:
 
* How many Vine reviews and non-Vine reviews were there?
    * Vine Reviews: 1,203
    * Non-Vine reviews: 58,018
    ![Review_Counts](https://user-images.githubusercontent.com/107375554/193724728-ce102f0e-1a1d-4721-99dd-3ae5fc05660e.png)

* How many Vine reviews versus non-Vine reviews were 5 stars? 410
    * 5-Star Vine Reviews: 410
    * 5-Star Non-Vine reviews: 28,043
    ![5_Star_Reviews](https://user-images.githubusercontent.com/107375554/193724763-778180ef-eca1-4211-9205-67a65bbba545.png)


* What percentage of Vine reviews versus non-Vine reviews were 5 stars?
    * 5-Star Vine Reviews: 1.44%
    * 5-Star Non-Vine reviews: 98.56%
    ![percent_paid_unpaid_reviews](https://user-images.githubusercontent.com/107375554/193724806-9bfbfed4-bb1b-41f5-898d-9e9e3e81b738.png)



## Summary: 

Based on this data, there is not sufficient evidence to suggest that the paid reviews from the Vine program created a bias in the reviews. The Vine program contributed about 1,000 of the total reviews compared to the 58,000 unpaid reviews. They also only made up 1% of the 5-star reviews. This does not suggest a significant bias in the 5-Star ratings. 

One additional analysis that could be done is to gather information on 1-Star ratings. We can count total Vine versus non-Vine 1-Star reviews as well as calculate percentages to see if the Vine program is bias in lower ratings. 
