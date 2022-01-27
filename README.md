# Big-Data-Amazon-Reviews
First goal is to perform the ETL process completely in the cloud  and upload a DataFrame to an RDS instance from two big Amazon customer review datasets.
For that two datasets were selected.First one is Watch reviews dataset and second one is Toys review dataset.

The second goal is to use PySpark or SQL to perform a statistical analysis on whether reviews from Amazon's Vine program are trustworthy.
Amazon watch review data set was selected for Vine review Analysis.
Pyspark was used to do the analysis.

**Summary of Analysis**

Total Number of paid reviews is 1747 and unpaid reviews is 958932.Out of that only the data with total votes >=10 is being analyzed.
So now the total Number of paid reviews is 130 and unpaid reviews is 27592. 
Percentage of paid reviews with 5 star rating is 33.85 ,whereas for nonvine reviews is 45.98.
As per this analysis it can be assumed that the Vine reviews are not biased.
