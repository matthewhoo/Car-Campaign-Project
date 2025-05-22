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

<p align="center">
  <img src="https://github.com/user-attachments/assets/4353614e-5905-40dc-b804-90650ccf2104" width="850" alt="Screenshot 2025-05-22 at 2 28 51 PM">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/f6965180-ed8b-41d2-acf6-64aa825c6bad" width="750" alt="Screenshot 2025-05-22 at 2 29 52 PM">
</p>


## Executive Summary
This car campaign analysis of approximately 5.4 million ad serving records (2022-2024) shows that campaigns are most profitable when broad reach formats are paired with precise retargeting. Banner-Ad retargeting and Certified-Video executions produce the highest deliverd traffic (user access website) and conversion efficiency, white Audio and poorly targeted Connected-TV spend generate minimal returns. Quarter over quarter trends reveal that the increase of impressions stopped translating into traffic after mid 2023, signalling a ROI shift. Geographic scoring further pinpoints poor preformance in GA, AK, NV, and IA, whereas New York and Los Angeles are able to convert strongly when strategy channel fit is optimised. Redirecting budget towards mid to top-performing channels, applying quarterly benchmarks, and reallocating spend away from underperforming states is expected to address dirft and improve overall campaign ROI in the next fiscal cycle.

## Insight Deep Dive
- ### Channel Efficiency Over Time
  - Banner Ads have emerged as the most effective channel, showing continous growth in delivered traffic since 2022 and surpassing all other formats by 2023. This trend indicates strong audience engagement and high return on marketing investment, supporting increased allocation of spend and resources toward Banner Ads in future campaigns.
  - Video performance has remained static despite overall increase in marketing volume. The lack of growth in traffic contribution form this channel suggests diminshing marginal returns, pointing to a need for a creative change or strategy.
  - Connected TV has contributed moderately and consistently, offering steady buy limited value. While not a top preformer, its reliability may make it suitable for targeted or complementary campaigns, particularly where long form engagement is desired.
  - Audio campaigns continue to underperform, with minimal traffic contribution acorss all quarters. Given limited impact over multiple years, these campaigns may require strategic repositioning or could be deemphasized in favor of other higher yielding channels.
<p align="center">
  <img width="800" alt="Screenshot 2025-05-22 at 2 57 22 PM" src="https://github.com/user-attachments/assets/aa2bb1df-fb10-4738-81b6-8e85562b7293" />
</p>

- ### ROI Drift: Impressions vs. Delivered Traffic
  - The year-over-year analysis highlights how early campaign success was driven by strategic precision, but as scale increased, eficiency declined. In Q1 2023, delivered traffic surged up to 98% despite only minial increases in impressions and actions, indicating that early campaign efforts were highly targeted and effective in converting reach into meaning outcomes or traffic.
  - However, as campaigns scaled into late 2023, the relationship between spend and outcome began to weaken. Large increases in impressions yielded minimal gains in delivered traffic, signaling the ROI drift. Engagement improved during this periodm but conversion (measured w/ DT) dailed to keep up to pace, suggesting that even with more users interacting, fewer were taking valuable actions.
  - By Q3 2024, efficiency had declined further: impressions and actions rose, but delivered traffic fell. The data strongly indicated that more exposure does not guarentee more value, and without active campaign governance, performance can erode even as spend increases.
  - To protect efficiency long term, campaign strategy should shift towards maintaining conversion quality over maximizing reach.
  
<p align="center">
  <img width="1000" alt="Screenshot 2025-05-22 at 3 10 52 PM" src="https://github.com/user-attachments/assets/281fe48a-c8f3-469c-9756-f41bbe052436" />
</p>
<p align="center">
<img width="800" alt="Screenshot 2025-05-21 at 4 29 12 PM" src="https://github.com/user-attachments/assets/2d569215-7279-4443-8fd2-89fd90ceb112" />
</p>

- ### ROI Trends Over Time
Early-2023 campaigns illustrate that precise audience targeting can unlock outsized returns: a 97 % lift in delivered traffic was achieved on only ~16 % more impressions, confirming that incremental spend is most valuable when it reaches high-intent users. As budgets expanded through Q3-2023, that relationship unraveled—traffic flat-lined while exposure kept rising, signalling ROI drift and the diminishing marginal value of additional reach. A brief rebound in Q2-2024, when impressions contracted yet traffic advanced 22 %, shows that removing low-quality inventory can immediately restore efficiency. By Q3-2024 all core metrics softened, indicating saturation and creative fatigue. The pattern underscores a key operational insight: sustained performance depends less on volume growth than on continuous pruning of under-performing segments and timely refresh of targeting and creative.

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/21e569a0-457c-4227-bd7f-6a9b428c7b5a" width="600" alt="Screenshot 1"/>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/c7fd13f2-5409-4cf2-9193-94758e1ec879" width="375" alt="Screenshot 2"/>
    </td>
  </tr>
</table>

 - Across all top-performing campaigns, RETARGETING consistenly appears as the most effective tactic, regardless of channel. Campaigns that focused on re-engaging users previously exposed to the brand generated higher delivered traffic and stronger conversion, indicating that follow-ups play a critical role in campaign success.
 - The most effective combinations often involved Banner Ads or Video as the channel, paired with either Retargeting or CDP Custom Audiences.
 - Certified campaigns showed a slight edge in efficiency over New Car campaigns when paired with targeted tactics. This suggests that Certified buyers may respong more to personalized or trust building formats, while NEw Car strategies may require more attention to creative and messaging alignment.
 - The common pattern among high performing combinations is a balance between scale and targeting. Campaigns that achieved both high DT and strong DT per impression tend to combine broad reach channels with precise audience segmentation, reinforcing hybrid targeting strategies in marketing performance.

<p align="center">
  <img width="900" alt="Screenshot 2025-05-22 at 3 22 07 PM" src="https://github.com/user-attachments/assets/393516f4-ba56-465b-848d-8b08a84e36bd" />
</p>
<p align="center">
  <img width="450" alt="Screenshot 2025-05-21 at 5 08 28 PM" src="https://github.com/user-attachments/assets/987669e4-5605-45d6-8432-2198e463e3c1" />
</p>




