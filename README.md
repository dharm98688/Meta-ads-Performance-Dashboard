📊 Meta Ads Performance Dashboard

An interactive Power BI dashboard designed to analyze the performance of Meta (Facebook & Instagram) advertising campaigns.
This project evaluates campaign effectiveness using key marketing KPIs such as CTR, Engagement Rate, Conversion Rate, Purchase Rate, and Audience Demographics.

The dashboard helps identify high-performing ad formats, target audiences, engagement patterns, and campaign optimization opportunities.

🛠 Tools & Technologies
📊 Power BI
📈 DAX (Data Analysis Expressions)
🧹 Data Cleaning & Transformation
🔗 Data Modeling
📉 Data Visualization
📂 Dataset Overview

The project uses four relational tables to simulate a real-world digital marketing analytics scenario.

1️⃣ Ad Events Table (ad_events)

Contains records of user interactions with ads.

Columns:

event_id → Unique event identifier
ad_id → Ad identifier
user_id → User identifier
timestamp → Time of the event
day_of_week → Day when interaction occurred
time_of_day → Hour of interaction
event_type → Type of event (click, share, comment, purchase, etc.)

This table is mainly used for calculating engagement metrics and conversion events.

2️⃣ Ads Table (ads)

Contains details about each advertisement.

Columns:

ad_id → Unique ad identifier
campaign_id → Associated campaign
ad_platform → Platform (Facebook / Instagram)
ad_type → Ad format (Video, Carousel, Image, Stories)
target_gender → Targeted gender audience
target_age_group → Target age range
target_interests → Target audience interests

This dataset helps analyze ad format performance and targeting strategy.

3️⃣ Campaigns Table (campaigns)

Contains campaign-level information.

Columns:

campaign_id → Unique campaign identifier
name → Campaign name
start_date → Campaign start date
end_date → Campaign end date
duration_days → Campaign duration
total_budget → Total campaign budget

This table is used to evaluate campaign budget utilization and performance.

4️⃣ Users Table (users)

Contains demographic information about users interacting with ads.

Columns:

user_id → Unique user identifier
user_gender → Gender of the user
user_age → Age of the user
age_group → Age category
country → User country
location → City/region
interests → User interest categories

This table is used to analyze audience demographics and geographic engagement patterns.

📈 Key KPIs

The dashboard tracks important digital marketing performance metrics:

Impressions
Clicks
Shares
Comments
Engagements
Purchases (Conversions)
CTR (Click Through Rate)
Engagement Rate
Conversion Rate
Purchase Rate
Total Campaign Budget
Average Budget per Campaign

These metrics help evaluate both awareness and conversion funnel performance.

📊 Dashboard Preview

The Power BI dashboard provides an interactive view of Meta advertising performance, highlighting campaign reach, engagement patterns, audience insights, and ad format effectiveness.

Dashboard Components

📌 KPI Cards

Impressions
Clicks
Engagements
Purchases
CTR
Engagement Rate
Conversion Rate
Purchase Rate
Campaign Budget

📌 Audience Insights

Impressions by Gender
Impressions by Age Group

📌 Geographic Analysis

Country-wise engagement distribution

📌 Time-Based Trends

Weekly impression trends
Hourly impression trends

📌 Ad Performance Comparison

CTR by ad type
Engagement rate by ad type
Conversion rate by ad type

Interactive filters allow users to analyze campaigns based on campaign name, interests, and marketing metrics.

🔍 Key Insights

📢 Campaign Performance

Ads generated 69K impressions and 8.23K clicks, resulting in a CTR of ~11.76%, indicating strong ad creatives and targeting.
Engagement rate of ~13.57% shows strong audience interaction.

💰 Conversion Funnel

The purchase rate is only ~0.61%, showing a drop-off in the lower funnel.
Indicates the need for landing page optimization and retargeting strategies.

🎥 Ad Format Performance

Video ads achieved the highest CTR and engagement rate.
Stories ads generated the highest impressions.
Image and Carousel ads performed moderately.

👩 Audience Insights

Female users generated the highest engagement.
The 18–30 age group showed the strongest interaction with ads.

🌍 Geographic Trends

Top engaged regions include:

United States
India
Brazil
Germany
United Kingdom

India and the US show high engagement potential, while Germany and the UK offer higher purchasing power markets.

⏰ Time-Based Trends

Engagement peaks during afternoon and evening hours (15:00–20:00).
Early morning hours show the lowest interaction levels.
