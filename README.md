# StarbucksCapstone

This is my capstone project for the Data Scientist Nanodegree program. 

Starbucks provided a simulated dataset on a series of A/B tests wherein Starbucks app members are issued seven promotional offers over a 30 day period. Data includes person and offer characteristics, and a complete event history in six-hour intervals.

There are 10 distinct promotional offers, each of which has different features. At each of the seven assignment dates, about 75% of the members are randomly assigned one of the ten possible offers and about 25% of the members are assigned to the no-offer control group. Offer types include buy-one-get-one-free, discount, and informational. Offers vary in duration from three days to ten days, where duration refers to availability for offers with monetary savings and assumed period of influence for informational offers. Offers with monetary savings vary in reward value. Offers were issued using different subsets of mediums, which can include web, email, mobile, and social. It appears that offer issue dates were randomly determined, but I cannot confirm this (technically I don't know if random assignment occurred with offers either, but F-tests suggests assignment is at least effectively random).

Member characteristics include membership enrollment date, age, gender, and income. 2,175 of the 17,000 members are missing all characteristics except enrollment date.

Event history includes offer receipts, offer views, offer completions with reward amounts, and transactions with purchase amounts.
