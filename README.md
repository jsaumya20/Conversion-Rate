# Conversion-Rate
![image](https://user-images.githubusercontent.com/91350558/208845303-094c7f8b-1d0b-4062-a69a-cac42ffb3b9e.png)

Predict conversion rate of the users on the website and provide conversion rate improvement suggestions.

## Goal

Optimizing conversion rate is likely the most common work of a data scientist, and rightfully so. The data revolution has a lot to do with the fact that now we are able to collect all sorts of data about people who buy something on our site as well as people who don't. This gives us a tremendous opportunity to understand what's working well (and potentially scale it even further) and what's not working well (and fix it).
The goal of this challenge is to build a model that predicts conversion rate and, based on the model, come up with ideas to improve revenue.
This challenge is significantly easier than all others in this collection. There are no dates, no tables to join, no feature engineering required, and the problem is really straightforward.

## Challenge Description

We have data about users who hit our site: whether they converted or not as well as some of their characteristics such as their country, the marketing channel, their age, whether they are repeat users and the number of pages visited during that session (as a proxy for site activity/time spent on site).
Your project is to:

#### •	Predict conversion rate
#### •	Come up with recommendations for the product team and the marketing team to improve conversion rate

## Data 

country : user country based on the IP address

age : user age. Self-reported at sign-in step

new_user : whether the user created the account during this session or had already an account and simply came back to the site

source : marketing channel source

Ads: came to the site by clicking on an advertisement SEO: came to the site by clicking on search results

Direct: came to the site by directly typing the URL on the browser total_pages_visited: number of total pages visited during the session. 
This is a proxy for time spent on site and engagement during the session.

converted: this is our label. 1 means they converted within the session, 0 means they left without buying anything. 

### The company goal is to increase conversion rate: # conversions / total sessions.

## Recommendations

Based on my findings, I propose the following to the marketing team.
1. Chinese users have an extremely low conversion rate. The company must improve its targeting of Chinese users.

2. Total pages visited is one of the important feature of the model, so company should try to increase user engagment on there website either by adding polls or    quizes and thereby rewarding coupons at the end of quizes, this will also help in attracting new customer base.

3. While younger users are doing well, company appear to be losing older users.

4. Older accounts convert at a higher pace. We may target new users with promotional offers and ad campaigns to entice them to visit our website more frequently.

5. If a person has viewed several pages but has not yet converted, we should utilize comparable targeted tools to persuade them to do so.

6. Younger generation & users in Germany do really well on our site, and we should target ad campaigns to attract younger and new German users.

*******THANK YOU*******
