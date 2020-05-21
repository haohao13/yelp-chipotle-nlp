# Yelp Review Analysis for Chipotle with Natural Language Processing
## Objectives

In this project, we aim to apply several natural language processing tools to analyze reviews of Chipotle Mexican Grill on Yelp from 2005 to 2018 to discover improvement rooms and propose suggestions for Chipotle.

## Data Resource

We merge the “business” table and the “review” table in Yelp Challenge Dataset, and extract Chipotle’s information. There are 9590 reviews of Chipotle in total.

Yelp Challenge Dataset is an open source dataset so that you can easily follow my analysis procedure if you are interested. The data resource link is here: https://www.yelp.com/dataset/challenge

## Structure

Exploratory Data Analysis Text Preprocessing Sentiment Analysis Word Clouds Topic Modeling

- Determining the optimal number of topics
- Finding key words for each topic using optimal LdaMallet model
- Determining the dominant topic in each review
- Combining Topic Modeling and Sentiment Analysis Pain Point Analysis
- Correlation between the percentage of one single word among positive/ negative reviews and review stars (based on time-series sentiment analysis)

## Recommendations

To provide customers with better experience, we recommend to Chipotle in the areas of ingredient quality, wait times and digital ordering.

- Improve the freshness and quality of its ingredients to regain its strategic strength.
- Investigate the supply chain to see how to improve the quality and taste of its proteins, especially chicken.
- Investigate the current quality of its most important product, burrito, which has gone fewer and fewer positive reviews.
- Improve online ordering system and mobile app, in order to better solve the wait time problem and improve customers’ buying experience.

If you are intereted about the detailed analyzing process, please visit: https://towardsdatascience.com/yelp-review-analysis-for-chipotle-with-natural-language-processing-bf4b3e5db140
