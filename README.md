# Amazon_Vine_Analysis

## Overview of the analysis:
Using our knowledge of the cloud ETL process, we created an AWS RDS database with tables in pgAdmin, pick a dataset on toy reviews from the Amazon Review datasets

Using our knowledge of PySpark, Pandas, or SQL, we determined if there is any bias towards reviews that were written as part of the Vine paid review program.


## Results:
 
* How many Vine reviews and non-Vine reviews were there?
    * Vine Reviews: 1,203
    * Non-Vine reviews: 58,018

* How many Vine reviews versus non-Vine reviews were 5 stars? 410
    * 5-Star Vine Reviews: 410
    * 5-Star Non-Vine reviews: 28,043

* What percentage of Vine reviews versus non-Vine reviews were 5 stars?
    * 5-Star Vine Reviews: 1.44%
    * 5-Star Non-Vine reviews: 98.56%


## Summary: 

Based on this data, there is not sufficient evidence to suggest that the paid reviews from the Vine program created a bias in the reviews. The Vine program contributed about 1,000 of the total reviews compared to the 58,000 unpaid reviews. They also only made up 1% of the 5-star reviews. This does not suggest a significant bias in the 5-Star ratings. 

One additional analysis that could be done is to gather information on 1-Star ratings. We can count total Vine versus non-Vine 1-Star reviews as well as calculate percentages to see if the Vine program is bias in lower ratings. 
