# Amazon_Vine_Analysis

## Overview
PySpark was used to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin, checking for bias toward favorable review from Vine members.


## Results

### Deliverable 1: Perform ETL on Amazon Product Reviews

* **Amazon_Reviews_ETL.ipynb** :  

* **The customers_table DataFrame** :  
![Screen Shot 2022-03-14 at 2 06 41 PM](https://user-images.githubusercontent.com/93094482/158234521-ff8aa273-f79a-4b40-b5b7-d9c43a5f2340.png)



* **The products_table DataFrame** :  
![Screen Shot 2022-03-14 at 2 06 49 PM](https://user-images.githubusercontent.com/93094482/158234573-8ea3cdc5-3165-4011-b1d0-e51fdcfe0e68.png)


* **The review_id_table DataFrame** :  
![Screen Shot 2022-03-14 at 2 06 57 PM](https://user-images.githubusercontent.com/93094482/158234599-513dc219-1cc7-4ba2-8857-8cd3a4760165.png)


* **The vine_table DataFrame** :  
![Screen Shot 2022-03-14 at 2 07 04 PM](https://user-images.githubusercontent.com/93094482/158234628-71ba54a9-113e-4e7a-807e-e8394e48d87d.png)



### Deliverable 2: Perform ETL on Amazon Product Reviews

-----------------------------------------------------------------------------
* There are 149086 total reivews
* There are 129709 5-star reviews


-----------------------------------------------------------------------------
* There are total 0 vine (vine = Y) reviews
* There are 0,Five-star vine (vine = Y) reviews
* There are 0.0% 5-star vine (vine = Y) reviews


-----------------------------------------------------------------------------
* There are total 149086 non-vine (vine = N) reviews
* There are 129709 5-star non-vine (vine = N) reviews
* There are 87.0% 5-star non-vine (vine = N) reviews


-----------------------------------------------------------------------------

## Results

### State if there is any positivity bias for reviews in the Vine program
There are no paid reviews and the approval for unpaid reviews is 87%. There is no positivity bias detected.
We could check lower ratings for bias such as 4-star.


