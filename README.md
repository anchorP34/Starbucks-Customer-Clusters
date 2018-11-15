# Starbucks-Customer-Clusters
Exploratory data analysis of Starbucks customers and grouping them into clusters.

You can see my blogpost for this project here: https://medium.com/@paytonsoicher/what-type-of-starbucks-customer-are-you-72f70e45f65

# Project Overview
This Starbucks project was my capstone project for the Udacity Data Scientist Nanodegree. This data was provided by Starbucks to simulate their customers and transactions to see if there are better approaches to sending customers specific promotional deals. I really enjoy unorthodox projects, and I had never done any type of clustering project with scenario data before so I really wanted to get out of my comfort zone for this one.

One important segment of any business is to look for areas that can be improved to save money or create more revenue. I was determined to look to see how well certain promotions were being used by all customers and to try and see what was a more effective method to offering promotions. Once I could see how people normally reacted, the problem then became to find a better way to make sure that the right people were receiving the right promotions.

I used exploratory analysis to see what type of customers existed in the Starbucks universe, their transaction / promotional engagement habits, and created a customer matrix dataframe that gae the whole view of what type of customer they were. The best machine learning approach was then to use a clustering method that could break up customers into different segments that would respond differently to different promotional deals.

By doing this, Starbucks can allocate their promotional deals in a more effective manner. People who come back on a regular basis dont need buy one get one free deals, but should receive discount deals. That way those customers still feel rewarded for being a customer, while Starbucks saves some money that they were giving away. People who might not be able to afford coming into Starbucks stores at a constant basis or don't go regularly for their own reasons should be given BOGO deals to reengage their interests in Starbucks and make them a more reliable customer.

These clustering methods found those specific people, grouped them together, and would give Starbucks a great idea of who their customers are, what cluster they fit in, and which promotional deal they should receive. 




# Profile Portfolio and Transcript Data.zip
Three JSON files that show profiles of customers, promotional deals that are offered, and the transaction history of customers.

##portfolio.json

id (string) - offer id
offer_type (string) - type of offer ie BOGO, discount, informational
difficulty (int) - minimum required spend to complete an offer
reward (int) - reward given for completing an offer
duration (int) - UNKNOWN
channels (list of strings)

##profile.json

age (int) - age of the customer
became_member_on (int) - date when customer created an app account
gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
id (str) - customer id
income (float) - customer's income

##transcript.json

event (str) - record description (ie transaction, offer received, offer viewed, etc.)
person (str) - customer id
time (int) - time in hours. The data begins at time t=0
value - (dict of strings) - either an offer id or transaction amount depending on the record


# Starbucks Capstone Project.ipynb
Jupyter Notebook that shows the start to finish of the this project. This starts with data cleanup and exploration, top level statsitics of customers and their transactions, and cluster analysis for better approaches of sending customers promotions.




