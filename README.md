# Amazon_Vine_Analysis

## Overview

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. In this analysis, we analyzed the vine reviews of watches on Amazon. The purpose of this analysis was to determine whether or not there bias toward favorable reviews from Vine members in the watches review dataset.

## Findings

The below provides a breakdown of our findings in review quality/outcome for paid and unpaid reviews. In the watches category, there were 8362 unpaid reviews, and 47 paid reviews.

Paid Reviews Breakdown:
* Total Reviews 47
* Total 5-Star Reviews: 15
* 5 star review ratio: 31.9%

Unpaid Reviews Breakdown:
* Total Reviews: 8,362
* Total 5-Star Reviews: 4332
* 5 star review ratio: 51.8%

## Summary

In looking at the results for paid vs. unpaid watch reviews, there does not appear to be a noticeable amount of bias based on the analysis conducted. Our focus group of paid reviews registered a significantly lower rate of five star revies (31.9%) compared to unpaid reviews (51.8%). If there were a correlation between paid reviews and 5-star ratings, we would expect to see a higher ratio of 5-Star scores in our "paid" category. To test this correlation, I would recommend conducting a statistical analysis in R, utilizing regression testing and t-tests.
