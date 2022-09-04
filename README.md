# Amazon_Vine_Analysis

##  Overview 

The purpose of this project was to conduct a meta-analysis of Amazon reviews and  to analyze reviews produced as part of the Amazon Vine program, where selected Amazon's reviewers are compensated to review sample products. The primary goal of this inquiry is to determine if there is any bias towards favorable reviews from the paid Vine members in the available data. ETL process is performed using PySpark and is connected to an AWS RDS instance. Pandas is used to determine if there is any bias towards favorable reviews from "Amazon Vine" members.

##  Results
Based on Video Game dataset:

There are only 44 Vine reviews.
26 of Vine reviews gave 5-stars.

Approximately 44% of Vine reviews were 5-stars.
There are 8661 non-Vine reviews.
3,233 non-Vine reviews gave 5-stars.
Approximately 37% of non-Vine reviews were 5-stars.


## Summary


Based on this analysis, there is a positive bias toward five-star reviews from paid Amazon Vine reviewers. This dataset contains a varity of video game consoles. As a result of this large variety of products, this analysis cannot be applied to individual products, but rather the dataset as a whole. Therefore, this conclusion could be further examined by conducting a more thorough analysis across a few different product catagories.
