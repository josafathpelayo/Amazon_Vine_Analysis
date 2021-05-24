# Amazon_Vine_Analysis

## Overview
The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. Out of the 50 datasets possible, the video games reviews was picked and with PySpark, the ETL process via AWS RDS instance and load the tranformed data into pgAdmin. Further more, PySPark was also used to determine if any bias reviews were written as part of the Vine program.

## Results

  - How many Vine reviews and non-Vine reviews were there?
    - There was a total of 94 reviews from the paid Vine reviews.
    - There was a total of 40471 reviews from the un-paid non-Vine reviews.
    
  - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    - A total of 48 out of 94 reviews were 5-Stars for Vine reviews
    - A total of 15663 out of 40471 reviews were 5-Stars for non-Vine reviews
    
  - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - 51.06% of Vine reviews were 5 stars
  - 38.7% of non-Vine reviews were 5 stars
  
 ## 
Looking at the data collected, one can see a bias when it comes to those who are part of the Vine program. As mentioned, memebers in the program must write a review on the product they purchase, so due to this fact where the probablility of a Vine memebers to write a 5 star review on a video game product is high. Based on the fact that 51.06% of Vine reviews were 5 stars, where as only 38.7% of non-Vine shoppers provided witha 5 star feed back. Then again, when looking at the total rieviews, 94 were from Vine members whereas 40471 were from non-Vine members. The Sample data is a bit skewed as non-vine reviews has about 430 times the reviews compared to Vine reviews. Other test that can be done is to get the descriptive start of all reviews and possibly group 4-5 star reviews together for a more in depth analysis.
