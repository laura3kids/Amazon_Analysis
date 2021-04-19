# Amazon_Analysis

## Overview of the Analysis:
The purpose of this analysis was to analyze the reviews from toys purchased on Amazon.  We used PySpark to extract, transform, and load the data so we could have a clean set of data to work with.  The purpose was to see if there was any bias towards a paid review versus an unpaid review. 

Using the Vine dataframe below, we were able to filter and answer specific questions regarding the dataset. 
![Vine_dataset](https://github.com/laura3kids/Amazon_Analysis/blob/main/Images/vine_table.png)

## Results:
The analysis showed the following results:

* Number of Paid and Unpaid Vine reviews: 
    * Total Number of Paid Vine Reviews: 1266
    * Total Number of Unpaid Vine Reviews: 62,028

* Number of 5-star reviews from Paid and Unpaid Vine reviews:
    * Number of Paid Vine 5-Star Reviews: 432 
    * Total Number of Unpaid Vine 5-Star Reviews: 29,982

* Percentages of Paid and Unpaid Vine 5-star reviews:
    * Percentage of Paid Vine 5-Star Reviews: 34.12% 
    * Percentage of Unpaid Vine 5-Star Reviews: 48.37%

#### Pyspark was used to calculate total number of reviews, 5 star reviews and percentages for Paid and Unpaid Vine reviews as shown below:


## Summary
After our dataset was cleaned, filtered, and transformed, we found just over 63,000 reviews in our Amazon Toy product reviews.  There was quite a difference in the number of Paid Vine Reviews (1266) compared to the Unpaid Vine reviews (62,028). In regards to the number of 5-star reviews, there were 432 Paid Vine reviews compared to 29,982 Unpaid Vine reviews.  When looking at 5-star reviews as a percentage of total reviews, there is a difference of 14.25%.  34.12% of the Paid Reviewers gave a 5-star review while 48.37% of the Unpaid reviewers gave a 5-star review. Based on these results, we do not believe we see any positivity bias in this review data. In order to prove bias, we would expect the number of paid reviewers to have a higher percentage of 5-star reviews compared to the unpaid users. To further assess if there is any bias between the paid and unpaid reviews, we could look at the 3-star and 4-star ratings to support further analsis whether any positivity bias is detected.
