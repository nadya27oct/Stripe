#### Overview

Data for 33 Merchants and their product usage for 2 years from 2013 to 2014.<br>
Most merchants are in Ecommerce, followed by Saas and Platform.<br>
In Ecommerce, 13 merchants use Cart, 9 merchantes use Marketplace and in SaaS, 7 merchants use API while 10 uses Recurring product. 

Merchants on Platforms using Marketplace have processed the largest volume of transactions in USD. <br>
Recurring product offered to SaaS users process the least amount of transactions across all products offered. <br>
Basic API product has a few merchants contributing to a large amount of transactions. <br>
Bimodal distribution of monthly payments processed by Platform merchants - a good number of merchants have a high volume of monthly transactions processed.

#### Cohort Analysis

After grouping customers based on their cohort month (first month of transactions), SaaS customers from the latest cohorts have processed lower transactions compared to the earlier cohorts in 2013. <br>
Even though Platforms account for most payments processed, Jan 2013 cohort seemed to be driving the majority of these payments. <br>
Somewhat concerning segment as latest cohorts (June & Aug 2013) have signficantly low volume of transactions processed over their active months. Additionally, no active merchants are available in recent months. <br>
Ecom merchants have a variablity in the payments processed through out their lifecycle, this segment is less concerning as the most recent cohort has an increasing engagement with Stripe. 

#### RFM segmentation

In order to segment merchants, I computed quartiles based on monthly transaction value, events count and tenure and aggregated a sum for each quartile. Merchants with most events and most transactions processed tend to have a longer tenure (23+ months). These are the power users. On average, merchants with lowest engagements (lower events and transactions processed) tend to be the most recent customers, i.e. they have a short tenure with Stripe products.

Some merchants worth looking at:

1. Merchant ID a9jszcl3di is a leading valuable customer. Even within such a short tenure - only 3 months since using Cart, they have processed a large volume of transactions - top 25th percentile. Perhaps they could be marketed with other products from Stripe.

2. Merchant ID 282t1vpldi in Saas and Ecom have a long tenure with Stripe. Yet they are least engaged with the products as indicated by low event count and low value of transactions processed. These two Merchants may not be worth going after. But it may be worthwhile to gain an idea of the low engagement rates - possible dissatisfaction with Stripe products.


#### Product Performance

Recurring products have an increasing trend in dollar transactions processed while lesser transactions are processed through manual charges. This is a good sign as Stripe plans to focus its efforts on promoting recurring subscriptions for its SaaS users.<br> 
However, the engagement for basic API is going up compared to recurring product. Perhaps the customer success team needs to look into understanding what is driving the high events count with Basic API. <br>
Additionally, top 50% of customers are driving a large proportion of revenue. It is worth looking into what factors contributed to their successful adoption of Recurring product.

Even though Markplaces account for largest overall $ value of transactions across all products, their overall monthly engagement (shown through events) and monetization (shown through $ transactions) levels have been constant in 2014. <br>
Merchants in Platform tend to have a high variation in their use of Marketplace, with bottom 50% Merchants contributing to less than $50000 transactions processed while the top 50% contribute to about $50,000-$150,000 transactions value.

Ecommerce - Revenue from ecommerce is somewhat cyclical, peaking around early Summer months. Distribution of $ transaction value vs number of payments submitted show that Merchants in this category are selling products at a constant price.











