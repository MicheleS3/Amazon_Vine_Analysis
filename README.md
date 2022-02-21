# Amazon_Vine_Analysis

## Overview

PySpark, AWS, and Postgres were used to analyze Amazon reviews for Jewelry to determine if reviews from Amazon Vine members are biased. The Jewelry dataset was chosen from Amazon and an analysis was conducted using PySpark to perform the ETL process, connect to an AWS RDS instance, and to load the transformed data into pgAdmin. PySpark was also used to analyze the dataset and determine the bias towards favorable reviews from Amazon Vine members.

## Results

- There was a total of 7,710 reviews of those reviews 21 are from paid Amazon Vine members and 7,689 are from unpaid Amazon Vine members.

![Jewelry Total Reviews Count](https://user-images.githubusercontent.com/89753083/155024765-f324dc78-d4b7-4fb1-9014-837ac209f392.PNG)

![Jewelry Paid Reviews Count](https://user-images.githubusercontent.com/89753083/155024798-2c378b22-d6ae-4167-8f0e-456e34892f74.PNG)

![Jewelry Unpaid Reviews Count](https://user-images.githubusercontent.com/89753083/155024812-d46a8ec3-3d32-4a19-9dde-682f23a5d642.PNG)

- A 5-Star review was given to 4,455 of those reviews 11 are from paid Amazon Vine members and 4,444 are from unpaid Amazon Vine members.

![Jewelry Paid 5-Star Reviews Count](https://user-images.githubusercontent.com/89753083/155025379-36873ccc-32e6-4ca9-9382-51a0fccfe7c0.PNG)

![Jewelry Unpaid 5-Star Reviews Count](https://user-images.githubusercontent.com/89753083/155025389-658d042d-6ce3-4128-8e97-dd90c06064f1.PNG)

A percentage of those 5-Star reviews 52% were from paid Amazon Vine members and 58% were from unpaid Amazon Vine members.

![Jewelry Paid 5-Star Reviews Percentage](https://user-images.githubusercontent.com/89753083/155025702-6d1e971d-ec47-4c63-9801-eee2e475186f.PNG)

![Jewelry Unpaid 5-Star Reviews Percentage](https://user-images.githubusercontent.com/89753083/155025718-46275a9c-c242-472d-98af-1a07709f6564.PNG)

## Summary

Comparing the percentage of reviews that were 5 stars from both Amazon Vine members and non Amazon Vine members, it can be concluded that there is no positivity bias for reviews of Jewelry in the Vine program. The percentage of five-star reviews from both groups are nearly the same with only a 6% variance. A similar analysis could be conducted to compare the one-star or lower reviews from both Vine and non-Vine members to further support this conclusion.
