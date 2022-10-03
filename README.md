# Amazon_Vine_Analysis

## Overview

Big Market helps businesses optimize their marketing efforts.  A client is preparing to release a large catalogue of products, but is curious if enrolling in a program that gives out free products to select reviewers is worth the cost. This exercise will be an introduction to Big Data, it’s handling systems and it’s handle processes with some of the leading technologies in association: Hadoop, MapReduce, and PySpark. There will also be a look into NLP, Natural Processing Language, Cloud services such as AWS, Amazon Web Services, and their beneficial relationships with Big Data. This project will use use AWS Simple Storage Service (S3) and relational databases for basic cloud storage to complete an analysis of an Amazon customer reviews.

### Data environment:
- AWS: S3, RWD
- PostgreSQL
- Google Colaboratory
- PySpark

## Results:

<img width="1375" alt="Screen Shot 2022-10-02 at 4 32 00 PM" src="https://user-images.githubusercontent.com/105556091/193646144-09948ef6-61da-43ad-93b0-a82c60aa0038.png">

Out of 918,702 reviews: 

- There are 20,314 Vine reviews 
  - There were 8,079, 5-star, vine reviews 
  - 39.7% of vine reviews rated 5-stars 
- There are 898,388 Non-Vine reviews 
  - 267,089, 5-star, non-vine reviews
  -  29.7% of the non-vine reviews rated 5-stars


## Summary 
Is there is any positivity bias for reviews in the Vine program? 

Yes, Although the unpaid reviews’ had a greater population set of 267, 089 reviews, the 5-star rating, from this group, was only 30% of their total votes.  Whereas the Vine reviews’ 5-star rating percentage was nearly half of the total vote, approximately 40%. Statistically speaking there is an apparent bias with the participants of the paid reviews program. 
In further analysis, it was determined that non-vine reviews had a 43% positive (4-5 star) rating and a 46% negative (1-2 stars) rating, where as, Vine reviews were determined to have a 62% positive rating and a 6% negative rating. Taking into account the overall grand scheme of the rating data (1-5 star ratings), rather than just the 5 star ratings, the statistics does indicate a bias of positive ratings among reviews that were incentivized. 

<img width="466" alt="Screen Shot 2022-10-02 at 4 25 27 PM" src="https://user-images.githubusercontent.com/105556091/193645930-8e73d4c3-ac80-4ac7-a392-97474c5c1e9b.png">
