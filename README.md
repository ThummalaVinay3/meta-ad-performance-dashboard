# - meta-ad-performance-dashboard

## 📌 Project Overview

This project presents an interactive Power BI dashboard developed using Meta (Facebook & Instagram) advertising data to analyze campaign performance, engagement, and ROI.
It provides marketing insights to optimize ad spend, targeting, and creative strategies, enabling better decision-making for digital marketing teams.


---
### 🎯 Objective

The main goals of this project are to:

Visualize key advertising metrics like Impressions, Clicks, CTR%, Engagement Rate, and Purchase Rate.

Compare ad performance across platforms (Facebook vs Instagram).

Understand audience behavior by gender, age group, country, and time.

Evaluate budget utilization and identify underperforming campaigns.

Provide actionable insights for improving ad effectiveness and ROI.

---

### 📁 Dataset

The dataset represents Meta Ads performance data modeled after how Facebook and Instagram track user interactions.

Key Tables:

ad_events: Logs ad interactions (Impressions, Clicks, Shares, Comments, Purchases).

ads: Defines ad creative details (platform, ad type, target gender, age group, interests).

campaigns: Contains campaign-level info (budget, duration, and strategy).

users: Captures demographics (gender, age, country, location, interests).

Key Metrics Captured:
Impressions | Clicks | Engagements | Purchases | CTR | Conversion Rate | Budget | ROAS

---

### 🧹 Data Cleaning & Preparation

Removed duplicates and null values from raw data.

Converted timestamps into date and time hierarchies (Month, Week, Hour).

Joined all tables using unique keys to form a Star Schema model.

Derived calculated fields for CTR, Engagement Rate, Conversion Rate, and Purchase Rate using DAX.

---
### 📈 Dashboard Features
1️⃣ Key Performance Indicators (KPIs)

Total Impressions

Total Clicks

CTR (%)

Engagement Rate (%)

Conversion Rate (%)

Purchase Rate (%)

Total Budget

Average Budget per Campaign

2️⃣ Audience Insights

Gender (Donut Chart): Engagement split by male, female, and other audiences.

Age Group (Bar Chart): Performance comparison across age groups.

Country (Map): Geographic view of campaign reach and engagement.

3️⃣ Time-Based Trends

Calendar Heatmap: Monthly activity to identify peak ad months.

Weekly Trend (Stacked Column): Weekly ad performance by ad type.

Hourly Trend (Area Chart): Hour-of-day engagement pattern.

4️⃣ Ad Type Performance

Matrix View: Compare ad formats (Image, Video, Story, Carousel) across Facebook and Instagram.

---
### 💡 Key Insights

CTR (11.76%) and Engagement Rate (13.56%) indicate strong top-funnel performance.

Purchase Rate (0.61%) reveals low conversion efficiency — opportunity to improve landing pages.

Top-performing audience: Females aged 18–30 from India and Brazil.

Best ad formats: Video and Story ads.

Peak engagement: Afternoon and evening hours (15:00–20:00).

Top countries: India, US, Brazil, Germany, and UK.

Insight Summary:
➡️ Ads attract attention effectively, but conversion can be optimized by improving the bottom funnel and refining targeting strategies.

---
### ⚙️ Technical Implementation

Built a Star Schema data model in Power BI with ad_events as the fact table and ads, campaigns, and users as dimension tables.

Created DAX measures for key KPIs: Impressions, Clicks, CTR%, Engagement Rate, Conversion Rate, and Purchase Rate.

Developed interactive visuals (donut, bar, heatmap, map, matrix, area chart) with dynamic metric switching.

Applied a clean, consistent layout and color theme for enhanced readability and storytelling.

---
### 🛠️ Tools & Technologies Used

Power BI Desktop → Data modeling, visualization, and report creation.

DAX (Data Analysis Expressions) → KPI calculations.

Excel / CSV → Initial data formatting.

Power Query → Data cleaning and transformation.

---
### 📂 How to Use

Download the .pbix file → Meta_Ad_Performance_Dashboard.pbix

Open it in Power BI Desktop (latest version).

Explore the interactive visuals and KPIs.

Switch metrics dynamically (Impressions, Clicks, Purchases) to explore trends.

---
### 🔍 Recommendations

📊 For Marketing Teams:

Focus on the 18–30 female demographic for better ROI.

Invest more in Video and Story ad formats.

💰 For Campaign Strategy:

Reallocate budget from low-performing campaigns to top-engagement segments.

🛒 For Conversion Optimization:

Improve landing page experience and call-to-action messaging.

---
### 🚀 Future Enhancements

Integrate cost-based metrics such as CPC, CPM, and ROAS.

Add predictive insights for ad performance forecasting.

Publish the dashboard on Power BI Service for real-time collaboration.

---
### ✅ Conclusion

This Power BI dashboard transforms raw Meta ad data into actionable business insights.
It helps marketing teams track performance, identify audience trends, and optimize budget for maximum return on investment.

With interactive visuals and data-driven KPIs, this project demonstrates how analytics can drive smarter digital marketing decisions.

---
### 📄 License

This project is open-source under the MIT License.

---
### 🏷️ Tags & Hashtags

#PowerBI #DataAnalytics #DashboardDesign #DataVisualization
#BusinessIntelligence #MarketingAnalytics #PortfolioProject
#DigitalMarketing #MetaAds #DataDriven #DataAnalyst
