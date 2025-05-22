# Car-Campaign-Project

## Project Background
This project aims to analyzes an anonymized dataset from a nation car company, collect during the years of 2022 to 2024 as part of a marketing performace evaluation. Operating within the automotive marketing industry, the company runs digital adverstising campaigns to drive consumer engagement and website dealership visits. The dataset includes millions of records detailing campaign strategy types (e.g, New Car vs. Certified), marketing channel types (e.g, Banner Ads, Connected TV, Video, Audio), device types, and key performance indicators like IMpressions, Actions, and Delivered Traffic (DT). This analysis was conducted using data shared with permission from a past internship and aims to identify high performing combinations of strategy and channel, showcase underperforming states or markets, and off data driven recommendations to optimize return on investments and campaign efficiency. 

- ### Channel Efficiency Over Time
  Evaluating the effecrtiveness of each marketing channel over time to reveal key insights about campaign ROI, audience behavior, and shifting cotent preferences. From 2022 to 2024, we reveal patterns that emerge showing a sharp rise in performance for specific channels like Banner Ads, while others like Audio remain minimal contributors. 

- ### ROI Drift: Impressions vs. Delivered Traffic
  Despite increased marketing efforts in recent quarters, delivered traffic (DT) has not seemed to scale proportionally with impressions and actions. This trend suggests a decline on return in investments and inefficiencies in certain campaign executions. To help ensure a more effective budget allocation, it is recommended to reassess channels or tactics where impressions are increasing with a corresponding increase in meaningful traffic (^ DT).

- ### ROI Trends Over Time
  Marketing effectiveness has fluctuated significantly over the past years, revealing a pattern of diminishing returns despite continued investment. While impressions and actions have increased steadily, delivered traffic (DT) has not always scaled proportionally. Understanding where and when ROI begins to drift helps decision-makers optimize spending and improve future campaign targeting.

- ### Underperforming Markets and Campaigns
  An analysis of market-strategy-channel performance highlights geographic and campaign-specific inefficiencies that are contributing to wasted impressions and under-delivered results. Despite high media spend and reach, certain states and combinations consistently return low delivered traffic (DT) or demonstrate poor efficiency, highlighting opportunities for targeted optimization.

## Data Structure
The dataset consists of ~5.4 Million records with the following key collumns:
- market, strategy, channel, tactic, device type
- day_of_week, date, year_month, state
- impressions, actions, dt, anomaly_outlier

<img width="1007" alt="Screenshot 2025-05-22 at 2 28 51 PM" src="https://github.com/user-attachments/assets/4353614e-5905-40dc-b804-90650ccf2104" />
<img width="543" alt="Screenshot 2025-05-22 at 2 29 52 PM" src="https://github.com/user-attachments/assets/f6965180-ed8b-41d2-acf6-64aa825c6bad" />

## Executive Summary
This car campaign analysis of approximately 5.4 million ad serving records (2022-2024) shows that campaigns are most profitable when broad reach formats are paired with precise retargeting. Banner-Ad retargeting and Certified-Video executions produce the highest deliverd traffic (user access website) and conversion efficiency, white Audio and poorly targeted Connected-TV spend generate minimal returns. Quarter over quarter trends reveal that the increase of impressions stopped translating into traffic after mid 2023, signalling a ROI shift. Geographic scoring further pinpoints poor preformance in GA, AK, NV, and IA, whereas New York and Los Angeles are able to convert strongly when strategy channel fit is optimised. Redirecting budget towards mid to top-performing channels, applying quarterly benchmarks, and reallocating spend away from underperforming states is expected to address dirft and improve overall campaign ROI in the next fiscal cycle.

