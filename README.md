# Amazon_Vine_Analysis

## Summary
Here in this module we utilize various technologies to get familiar with Pyspark. We review all the reviews of a certain category that participate in Amazons Vine review program. We consolidate the data from a database and analyze it to see what the impact on having the reviews essentially paid for vs not being in the program. We utilized AWS RDS, S3 storage, Google Collab, SQL, and PySpark to work with the data. 


## Results: Using bulleted lists and images of DataFrames as support, address the following questions:

How many Vine reviews and non-Vine reviews were there?

There were 4781 Paid Vine Reviews and 332395 non-Vine reviews

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

There was 1604 5 star vine reviews and 168800 5 star non-vine reviews

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

33% of the Vine reviews were 5 stars and 50% weren't.
![This is an image](https://i.imgur.com/CrjtDIm.png)

## Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

I would say that there ins't any positivity bias for reviews in the Vine program at least in the book section. We can see that a large majority of the reviews that were 5 star weren't in the vine program. To improve our analysis we can do more analysis on different catergories of reviews and see if they have a posativiy bias. We can increase the sample size by getting more reviews or we can filter the data frame for verified purchase or date. 
