# Amazon_Vine_Analysis
module 16 Big Data


## Overview

In this module we were introduced to big data. We used pyspark to analyze different reviews left on the Amazon Vine website. We performed ETL on the dataset to get an accurate count of how many reviews were left, paid and unpaid as well as how many 5-star reviews were left. We also used Amazon Web Services to connect to an RDS and load our data into pgAdmin. We used a bit of SQL to count and analyze the reviews. 

## Results

* How many Vine reviews and non-Vine reviews were there?
  94 vine reviews and 40,471 non-Vine reviews
  <img width="234" alt="paidreviews" src="https://user-images.githubusercontent.com/45208773/145683442-9ddcfb90-a019-4216-a139-692d6b56b913.PNG">
  <img width="254" alt="unpaid" src="https://user-images.githubusercontent.com/45208773/145683455-51f60339-e38e-4c49-8b63-f7a4cb5a7fb6.png">

  
  
 * How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
   48 paid 5-star reviews and 15,663 non-Vine 5-star reviews.
   
   <img width="427" alt="5starpaid" src="https://user-images.githubusercontent.com/45208773/145683474-5d00b588-8dad-4c1f-b410-d98a6d3a72fd.PNG">
  
   <img width="452" alt="5starunpaid" src="https://user-images.githubusercontent.com/45208773/145683498-482e8d59-2431-44d6-b7e0-0cc9c7f8f206.PNG">

   
   
 * What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
   51% of paid 5-star reviews and 39% unpaid 5-star reviews. 
   
   <img width="448" alt="percentpaid" src="https://user-images.githubusercontent.com/45208773/145683520-8f99768c-65b7-47dd-b147-c13a31f5c8f9.PNG">

   <img width="458" alt="percentunapid" src="https://user-images.githubusercontent.com/45208773/145683538-0f9f6500-36ad-47a0-b39c-aa7f09d4454f.PNG">

  
  ## Summary 
  There is a positivity bias in the Vine reviews because the percentage is 51% which is higher than the non-Vine reviews. To further analyze we could pick another product and analyze the reviews between vine and non-vine reviews to see if their truly is a bias towards vine reviews. 
