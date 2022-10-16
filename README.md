# Amazon_Vine_Analysis
## Overview Of The Analysis
The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. I will pick one dataset out of the 50 that were provide and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I'll use Pyspark to determine if there is any bias toward favorable reviews from Vine members in the dataset.
## Results
How many Vine reviews and non-Vine reviews were there?

![Total Number of Reviews](https://user-images.githubusercontent.com/105949411/196057635-174157ba-7cc5-4331-9489-3f0d303ac974.png)

There were 94 vine reviews and 40471 non-Vine reviews.

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

48 Vine reviews were 5 star. 15663 non-Vine reviews were 5 stars.

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

51.06% of Vine reviews were 5 star and 38.7% of non-Vine reviews were 5 star.
## Summary
There appears to be a positivity bias for the reviews in the Vine Program as 51.06% of the Vine reviews were 5 star and only 38.7% of non-Vine reviews were 5 star. In order to fully conclude that their is a positivity bias in the Vine Program more datasets would need to be ananlyzed first. It is possible that results found from the Video Game dataset are an outlier when compared to the whole.
