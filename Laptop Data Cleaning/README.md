# Introduction
In this project, an unclean dataset is taken from Kaggle that comprises details of data related to laptops. 
<br>
*Dataset*: [Laptop Data](https://www.kaggle.com/datasets/ankit07chy/laptopuncleaneddataset)

## Data Cleaning
Initially, there were no duplicates. But there were many blank fields that caused many problems later on. There were
no generalizations for many columns in this dataset. Hence, new columns had to be made to help categorize the scores
carefully. For the "Spec_Score", 0-40 is considered "Low-Tier", 41-69 is considered "Mid-Tier", and 70-100 is considered
Top-Tier. Consequently, the processors have been distinguished as well due to the ambiguity. One of the important
metrics is RAM in the current market, so RAM has been handled separately. Lastly, people like to sort laptops by
companies. So, a new column keeping companies in mind has been done as well. 

## Analysis Phase
In this phase, the average price has been analyzed based on the companies as well as the processors. A separate filter
is present to sort based on the RAM, which gives a clearer view on the prices. 

## Price Trend
A graph has been drawn to show the prices of the laptops based on the number of ratings, which shows a new perspective on the
number of buyers and the price of the laptops. 
