# Cyclistic Bike-Share: User Behavior & Ride Trends Analysis

![Dashboard Preview](https://github.com/AbiOsorioZ/Cyclistic-bike-share-analysis/blob/main/comparacion%20membresia-casual.png)

## Project Overview
Exploratory data analysis of ~4.9M rows of historical bike-share data from Cyclistic[cite: 18]. This end-to-end data analytics project investigates how annual members and casual riders use Cyclistic bikes differently. By cleaning, transforming, and modeling large datasets using Python (Pandas), and generating visual insights via Seaborn and Matplotlib, this study provides data-driven recommendations for converting casual riders into annual members.

## Key Questions Explored
* **How do annual members and casual riders use Cyclistic bikes differently?**
* **What are the usage patterns across days of the week for both user groups?**
* **What is the average trip duration comparison between members and casuals?**

## Tools & Technologies
* **Python & Google Colab:** Data ingestion, massive dataset concatenation, and scripting[cite: 18].
* **Pandas & NumPy:** Data cleaning, manipulation, datetime conversion, filtering negative/short rides, and aggregation (`groupby`)[cite: 18, 19, 20, 21].
* **Seaborn & Matplotlib:** Exploratory data visualization, custom color palettes, and multi-plot executive charts[cite: 22, 23].
* **Domain Knowledge:** Business intelligence, user segmentation, and conversion funnel optimization.

## Key Findings
* **Volume vs. Duration Disparity:** Annual members account for a higher total volume of trips (~3.17M vs. ~1.68M casual trips), demonstrating high frequency and routine usage (e.g., commuting)[cite: 21]. Conversely, casual riders exhibit significantly higher average trip durations (~23 min vs. ~12.5 min for members), indicating leisure or recreational use[cite: 21].
* **Weekly Behavioral Patterns:** Member trip volume peaks mid-week (Tuesday to Thursday)[cite: 22, 24], aligning with standard work schedules. In contrast, casual riders increase their activity during weekends (Saturday and Sunday)[cite: 22, 24].

## Data Cleaning & Transformation Workflow
* **Dataset Consolidation:** Merged 12 individual monthly CSV files containing nearly 5 million raw records into a single optimized DataFrame[cite: 18, 19].
* **Feature Engineering:** Extracted day of the week, day names, and calculated exact trip lengths in minutes from timestamps (`started_at` and `ended_at`)[cite: 19].
* **Data Quality Filtering:** Filtered out inconsistent records (rides with negative durations or lasting less than 1 minute due to dock checks), discarding 129,222 erroneous rows to ensure statistical integrity[cite: 19].

## Strategic Business Recommendations
* **Targeted Weekend Promotions:** Since casual riders peak on Saturdays and Sundays with longer durations, digital marketing campaigns should target leisure spots during weekends[cite: 22, 24].
* **Membership Conversion Incentives:** Design promotional pricing plans or weekend-to-weekday commuter passes tailored to frequent casual riders to encourage annual subscription adoption.

---
**Author:** Abigail Osorio ([abiosorioz.04@gmail.com](mailto:abiosorioz.04@gmail.com))
