# Amazon_Vine_Analysis
Overview:
In this project we are trying to determine if there is any bias toward favorable reviews from Vine members vs non-members.
We were given a dataset of various Vine Reviews for Wireless products.
We used PySpark to perform the ETL process on our data. We connected and AWS RDS instance and then loaded the trasformed data into pgAdmin. We also used PySpark to determine if there is any bias toward favorable reviews from Vine members in our dataset.

How many Vine reviews and non-Vine reviews were there?

•	Vine Reviews - 613

•	Non Vine Reviews - 64968

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

•	5 Star Vine Reviews - 220

•	5 Star non-Vine Reviews - 30765

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

•	% of 5 star Vine Reviews - 36%

•	% of 5 star non-Vine Reviews - 47%

 
 ![Vine](https://user-images.githubusercontent.com/58608736/149720221-a27cce88-18f8-4b3d-a30c-b0ea287093c9.PNG)

Summary:
We found that paid Vine members actually have a lower overall 5 star % than non Vine customers.

Further analysis is recommended to understand why the paid members have an overall lower star rating than non paid members.
