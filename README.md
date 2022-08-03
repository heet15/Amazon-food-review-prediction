## First We want to know What is Amazon Fine Food Review Analysis?
This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plaintext review. We also have reviews from all other Amazon categories.

Amazon reviews are often the most publicly visible reviews of consumer products. As a frequent Amazon user, I was interested in examining the structure of a large database of Amazon reviews and visualizing this information so as to be a smarter consumer and reviewer.

Source: https://www.kaggle.com/snap/amazon-fine-food-reviews

Introduction
The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.

Number of reviews: 568,454
Number of users: 256,059
Number of products: 74,258
Timespan: Oct 1999 — Oct 2012
Number of Attributes/Columns in data: 10
Attribute Information:
Id
ProductId — unique identifier for the product
UserId — unqiue identifier for the user
ProfileName
Helpfulness Numerator — number of users who found the review helpful
HelpfullnessDenominator — number of users who indicated whether they found the review helpful or not
Score — rating between 1 and 5
Time — timestamp for the review
Summary — brief summary of the review
Text — text of the review
Objective
Given a review, determine whether the review is positive (Rating of 4 or 5) or negative (rating of 1 or 2).

[Q] How to determine if a review is positive or negative?

[Ans] We could use the Score/Rating. A rating of 4 or 5 could be cosnidered a positive review. A review of 1 or 2 could be considered negative. A review of 3 is nuetral and ignored. This is an approximate and proxy way of determining the polarity (positivity/negativity) of a review.
