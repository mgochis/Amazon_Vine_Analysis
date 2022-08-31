# Amazon_Vine_Analysis
 
## Overview

Utilizing a product review database from Amazon we compared to difference between reviews of products that were part of the Vine program and products not part of the Vine Program. Amazon's Vine program lets sellers send free products to Amazon reviewers. The main task of this project was to determine if the reviewers receiving the free merchandise are influenced by receiving the product for free. Reviewers may be influenced to give a higher review of a product that they were given for free. I utilized a variety of technologies to accomplish this analysis, including AWS, SQL, PySpark, and Pandas. 

## Results

- How many Vine reviews and non-Vine reviews were there?
    - Vine reviews: 33
    - Non-Vine reviews: 45,388

- How many Vine Reviews were 5 stars? How many non-Vine reviews were 5 stars?
    - 5-star Vine reviews: 15
    - 5-star non-Vine reviews: 23733

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars? 
    - Percentage of 5-star Vine reviews: 45.5%
    - Percentage of 5-star non-Vine reviews: 52.3%

![Insert Image Here](https://github.com/mgochis/Amazon_Vine_Analysis/blob/b9e447a6fc69a3e686df53a79bca97b87c26826a/screenshot.png)

## Summary

There does not appear to be an increase of influence from reviews in the Vine program. There is potential evidence that the reviewers in the Vine program tend to be harsher than the non-Vine members. There isn't a sufficient amount of data to conclude the influence of the Vine program, since there are only 33 points of data. An additional analysis of the total average review score, not just 5-star reviews, could help to discover if there is a bias. 