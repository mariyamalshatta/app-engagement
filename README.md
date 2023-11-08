# app-engagement
test wether app engagement is better than the market

**Business Context**

AZ Tunes is a music streaming company and they analyze customer data to improve recommendations, playlists, and rollout special offers. Their persistent work to uncover and act upon evolving customer expectation has resulted in higher customer engagement time and subscription to their paid service.

**Objective**

The Marketing team of AZ Tunes wants to rollout special offers through a new campaign. As a data scientist, your objective is to help the team design the campaign by providing the below data-driven inputs:

According to a study, the average weekly app engagement time of users in leading music services is around 6 hrs. Can we claim that the app engagement time of AZ tunes is better than this market standard?
The team wants to spend their budget on the age group which has the highest chance of subscribing as part of their campaign
You need to perform statistical analysis on a sample of customer data and provide an evidence-based conclusion to help the marketing campaign succeed.

**Data Dictionary**

For this task, you are provided with a random sample of 1000 users along with their age group & engagement time on the AZ tunes app.

user_id: Unique user-id of the user
age_group: Age-group that the user belongs to
subscription_status: Whether the user is a subscribed user or a non-subscribed user
enagement_time: Weekly average of app engagement time (in hrs) of the user
Solution Approach
To solve the above problem, we need to answer 2 questions:

Is the average app engagement time of AZ Tunes significantly greater than the market average (6 hours)?
Is the difference in proportions of subscribers & non-subscribers (in 3 groups - under 18, 18-34, and over 35) significantly different to conclude that a particular group is most likely to subscribe?
