# Amazon_Vine_Analysis
 
## Overview

Utlizing a product review database from Amazon we compared to difference between reviews of products that were part of the Vine program and products not part of the Vine Program. Amazon's Vine program lets sellers send free products to Amazon reviewers. The main task of this project was to determine if the reviewers receiving the free merchandise are influened by receiving the product for free. Reviewers may be influenced to give a higher review of a product that they were given for free. I utilized a variety of technologies to accomplish this analysis, including AWS, SQL, PySpark, and Pandas. 

## Results

- How many Vine reviews and non-Vine reviews were there?
    - Vine reviews: 33
    - Non-Vine reviews: 45,388

- How many Vine Reviews were 5 stars? How many non-Vine reviews were 5 stars?
    - 5 star Vine reviews: 15
    - 5 star non-Vine reviews: 23733

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars? 
    - Percentage of 5 star Vine reviews: 45.5%
    - Percentage of 5 star non-Vine reviews: 52.3%

[Insert Image Here]

## Summary

There does not appear to be an increased of inflence from reviews in the Vine program. There is potential evidence that the reviewers in the Vine program tend to be more harsh than the non-Vine members. There isn't a sufficent amount of data to conclude the influece of the Vine program, since there are only 33 points of data. An additional analysis of the total average review score, not just 5 star reviews, could help to discover if there is a bias. 