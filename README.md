# Amazon_Vine_Analysis

## Overview
PySpark was used to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin, checking for bias toward favorable review from Vine members.


## Results

### Deliverable 1: Perform ETL on Amazon Product Reviews

* **Amazon_Reviews_ETL.ipynb** :  

* **The customers_table DataFrame** :  
<p align="left">
<img src = "https://github.com/dhaval-28/Amazon_Vine_Analysis/blob/main/Images/Customer_Table_DF.png" /><br>
</p>

* **The products_table DataFrame** :  
<p align="left">
<img src = "https://github.com/dhaval-28/Amazon_Vine_Analysis/blob/main/Images/Products_Table_DF.png" /><br>
</p>

* **The review_id_table DataFrame** :  
<p align="left">
<img src = "https://github.com/dhaval-28/Amazon_Vine_Analysis/blob/main/Images/review_id_table_DF.png" /><br>
</p>

* **The vine_table DataFrame** :  
<p align="left">
<img src = "https://github.com/dhaval-28/Amazon_Vine_Analysis/blob/main/Images/vine_table_DF.png" /><br>
</p>


### Deliverable 2: Perform ETL on Amazon Product Reviews
![click here for : Amazon_Reviews_ETL.ipynb file](https://github.com/dhaval-28/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb)


-----------------------------------------------------------------------------

* There are 149086 total reivews
* There are 129709 5-star reviews


-----------------------------------------------------------------------------
* There are total 0 vine (vine = Y) reviews
* There are 0,Five-star vine (vine = Y) reviews
* There are 0.0 % 5-star vine (vine = Y) reviews


-----------------------------------------------------------------------------
* There are total 149086 non-vine (vine = N) reviews
* There are 129709 5-star non-vine (vine = N) reviews
* There are 87.0 % 5-star non-vine (vine = N) reviews


-----------------------------------------------------------------------------
## Results

### State if there is any positivity bias for reviews in the Vine program
There are no paid reviews and the approval for unpaid reviews is 87%. There is no positivity bias detected.
We could check lower ratings for bias such as 4-star.


