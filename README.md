# Bike_sharing Dashboard
### Power BI Link: 

## Problem Statement
This dashboard was created to help a bike-sharing company analyze key performance metrics such as profitability, revenue patterns, rider behavior, and seasonal trends. The goal is to uncover when and where the company is most profitable, identify opportunities for pricing strategies, and make data-informed operational improvements.

The visualizations allow stakeholders to explore time-based profitability, revenue by season, and average rider metrics by type. The findings support better pricing decisions, resource allocation, and seasonal planning to drive business growth.

### Steps Followed

Step 1: Loaded two datasets (2021 & 2022) and merged them using a UNION ALL clause into a common CTE.

Step 2: Enriched the dataset by calculating Revenue (riders * price) and Profit (revenue - COGS).

Step 3: Cleaned the data by verifying nulls and ensuring cost data was joined correctly from cost_table.

Step 4: Imported the dataset into Power BI Desktop and initiated the report-building process.

Step 5: Used card visuals to display key KPIs such as:

Total Profit: $3.42M

Total Revenue: $5M

Step 6: Added a line and clustered column chart to show:

Sum of riders

Average of revenue and profit over time (dteday)

Step 7: Created a matrix visual titled "When are we making profit?" to analyze profits by hour and day.

Step 8: Incorporated seasonal insights through a bar chart showing Revenue by Season.

Step 9: Added donut chart to break down the average riders by rider type, helping identify customer segments.

Step 10: Built slicers for dynamic filtering by year, allowing users to toggle between 2021 and 2022 data.

Step 11: Performed price analysis and simulated conservative pricing strategy increases.

### Insights

1. When Are We Making Profit?
Peak Profit Hours: 3 AM to 5 AM had the highest profit margins across multiple days.

Top Performing Days: Days 16 and 17 showed the highest revenue spikes—possibly due to commuter routines or weekend demand.

This suggests targeted marketing or promotions during these hours could further boost profit.

2. Revenue & Profit Overview
Total Revenue: $5M

Total Profit: $3.42M

Indicates a healthy margin with potential for optimization through pricing.

3. Seasonal Trends
Season 3 (likely summer) was the most profitable with $1.67M in revenue.

Suggests resource ramp-up and pricing tweaks during this period for maximum yield.

4. Rider Type Analysis
Majority of the usage (80.11%) came from a dominant rider type—potentially commuters or subscribers.

Opportunity exists to create tiered pricing or membership plans tailored to rider profiles.

5. Delay or Downtime Indicators (if applicable)
While the current focus is on financials, extending this dashboard with bike availability or downtime metrics could further enhance operational efficiency.

### Pricing Strategy Recommendation
Considering the strong performance in 2021, a conservative price increase is suggested for 2022:

10% increase → $5.49

15% increase → $5.74

This range allows the company to test price sensitivity while maintaining customer loyalty. A segmented pricing approach based on:

Rider type

Season

Time of day
...can be implemented to maximize revenue without hurting demand.

### Conclusion
This single-page Power BI dashboard delivers an actionable overview of the bike-sharing business’s financial health and customer behavior. With dynamic filters and visual insights, stakeholders can now:

Monitor performance in real-time

Adapt pricing based on seasonality and user segments

Identify operational windows for high-impact decisions

