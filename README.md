# Yelp Review Predictions

Tina Lin &bull; 12/2017

&nbsp;
## Motivation

I chose yelp review dataset because I am a foodie and I find yelp reviews to be very useful. I would like to know whether there is a pattern in users’ reviews.
The four specific questions that I decided to explore for this dataset are:
1. What are the most popular words users have written in positive reviews?
2. What are the ten most frequent part of speech tags in the review text?
3. Some reviews are tagged as useful, funny or cool. Is there a correlation
between stars, useful, funny and cool? (i.e. if a review is tagged as useful, funny or cool, is it more likely to have a very high star or low star?) If a review is tagged as useful, is it more like to be tagged as funny or cool?
4. Can we predict whether a review is positive or negative by analyzing yelp review “text” column?

&nbsp;
## Data Source

I downloaded the yelp review csv file from (https://www.kaggle.com/yelp-dataset/yelp-dataset/data).
Here are the important variables and their types: 
1. review_id: text
2. user_id: text
3. business_id: text
4. stars: integer
5. date: date
6. text: text
7. useful: integer
8. funny: integer
9. cool: integer
I used the first 400,000 records, instead of all of them, for my analysis, to make it
run faster. The time periods the data covered are from 2004-07-22 to 2017-12-11.


&nbsp;
## User Guide
1. Dowload yelp review csv file from (https://www.kaggle.com/yelp-dataset/yelp-dataset/data).
2. Run yelp_review_prediction.py


