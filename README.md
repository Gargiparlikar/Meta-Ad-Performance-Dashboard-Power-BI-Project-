# 📊 Meta Ad Performance Dashboard (Power BI Project)
## 📝 Overview

This Power BI dashboard provides a complete analysis of Meta (Facebook + Instagram) advertising performance, helping marketers understand how their ads are performing across impressions, engagement, clicks, gender, age, geography, ad type, and budget usage.

The dashboard is designed with an interactive UI featuring dynamic measures, slicers, monthly calendar view, and multi-platform selection.

## 🎯 Problem Statement

Businesses running Meta ads often struggle to answer critical performance questions:

Which audience segments (age, gender, country) engage the most?

Which ad format generates the highest CTR, engagement, or purchase rate?

How do engagement trends vary hourly, weekly, and monthly?

Which campaigns are overspending or underperforming?

How effectively is the marketing budget being used?

The raw advertising data is large, complex, and multi-dimensional, making manual analysis slow and inefficient.
To solve this, we created an interactive Power BI dashboard that presents actionable insights in a clean and visual format for faster decision-making.

# 📸 Dashboard Preview

Add your screenshot inside the screenshots/ folder and update the image path below.
## 📂 Dataset Description

The dataset includes the following key fields:

Field	Description
Impressions	Number of times ads were viewed
Clicks	How many users clicked the ad
Purchases	Completed purchases
Shares, Comments, Engagments	User interactions
CTR	Click-through rate
ER	Engagement rate
Conversion Rate	Purchase conversions
Age, Gender, Country	Audience demographics
Ad Type	Carousel, Video, Stories, Image
Daily, Weekly, Monthly metrics	Time-based trends
Campaign Budget	Total amount spent
⭐ Dashboard Features
🔹 1. KPI Summary Cards

Impressions

Clicks

Purchases

Engagement

CTR

Conversion Rate

Average Budget per Campaign

Total Budget

Purchase Rate

🔹 2. Engagement Insights

Engagement by Age

Engagement by Gender (Donut Chart)

Engagement by Country (Map Visualization)

🔹 3. Trend Analysis

Weekly Engagement Trend

Hourly Engagement Trend

Monthly Calendar Heatmap

🔹 4. Ad Type Performance

A heatmap showing:

Impressions

Clicks

CTR

PR (Purchase Rate)

ER (Engagement Rate)

CR (Conversion Rate)

🔹 5. Dynamic Filters & User Controls

Select Platform → Facebook / Instagram

Select Dynamic Measure → Engagement, CTR, Purchases, etc.

Name filter

Target Interests filter

## 📈 Key Business Insights

✔ Ages 20–35 generate the highest engagements
✔ Females lead engagement share (~43%)
✔ Video Ads show highest CTR & ER
✔ USA, Europe & India top engagement regions
✔ Strong engagement patterns in morning & evening hours
✔ Weekly trends show spikes during weekends
✔ Stories vs Carousel reveal different engagement patterns

## 🛠 Tools & Technologies Used

Power BI Desktop

Power Query for Data Cleaning

DAX for Dynamic Measures

Maps, Heatmaps, Calendar Visuals

Custom Visuals (Dynamic Buttons, KPI Cards)


## 🧠 DAX Measures Used (Examples)
CTR = DIVIDE([Clicks], [Impressions], 0)

Engagement Rate = DIVIDE([Engagements], [Impressions], 0)

Purchase Rate = DIVIDE([Purchases], [Engagements], 0)

Budget Per Campaign = AVERAGE('Ads'[Budget])

## 🚀 How to Use the Dashboard

Open the .pbix file in Power BI Desktop.

Use the platform selector to switch between Facebook & Instagram.

Use dynamic measure dropdown to change metrics.

Explore insights by age, gender, geography, and ad type.

Use the calendar view to analyze month-wise performance.

## 📌 Future Enhancements

Add campaign-level drill-through pages

Incorporate ROI and CPM metrics

Add a Marketing Funnel visualization

Include prediction using Power BI ML

## 💡 Conclusion

This dashboard transforms raw Meta ad data into actionable insights, helping digital marketers optimize ad spending, target the right audience, and improve campaign performance.
