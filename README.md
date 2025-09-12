# Cyclistic Bike-Share Analysis
Capstone project from the **Google Data Analytics Professional Certificate**.  
This project analyzes Cyclistic’s bike-share data to understand rider behavior and provide recommendations for increasing annual memberships.

---

## Business Task
Cyclistic’s goal is to increase the number of annual members.  
As a junior data analyst on the team, the business question is:  

**"How do casual riders and annual members use Cyclistic bikes differently?"**

Deliverable: insights and recommendations that help the marketing team design a strategy to convert casual riders into annual members.

---

## Data Preparation
- **Source:** Divvy bike-share dataset (publicly available via Motivate International Inc).  
- **Tool:** R and RStudio.  
- **Files:** 12 months of trip data (CSV).  
- **Cleaning:**  
  - Removed null values and duplicates.  
  - Converted column names to consistent formats.  
  - Filtered out rides with unrealistic duration or distance.

---

## Data Processing
Steps in R / RMarkdown:
- Converted datetime columns (`started_at`, `ended_at`).  
- Created new variables: ride length, day of week, month.  
- Ensured data types are correct (e.g., factors for categorical).  
- Aggregated data to compare **casual vs member** usage.  

---

## Data Analysis
Key findings:
- **Ride length:** Casual riders take longer trips on average than members.  
- **Usage by day:** Casual riders ride more on weekends; members ride more on weekdays.  
- **Seasonality:** Casual rider usage spikes in summer; member usage is steadier year-round.  
- **Bike type:** Casual riders use docked bikes more frequently.

---

## Data Visualization
Examples (generated in R):
- Average ride length by user type.  
- Number of rides by day of week (casual vs member).  
- Monthly usage trends.  

*(Insert plots or screenshots here if available, e.g., from your `.Rmd` knit.)*

---

## Key Insights
- Casual riders: longer, leisure-focused trips, especially weekends and summer.  
- Members: shorter, commuter-focused trips, steady across the week.  
- Casual riders prefer docked bikes, while members mostly use classic or electric bikes.

---

## Recommendations (Share & Act)
1. Target weekend and summer promotions to casual riders.  
2. Incentivize membership by highlighting cost savings for frequent users.  
3. Emphasize convenience (e.g., faster unlocks, no dock requirement) to attract casual riders.  
4. Focus marketing campaigns in channels used by tourists and occasional riders.

---

## Files in this repo
- `CyclisticReport.Rmd` → full analysis code + narrative.  
- `CyclisticReport.html` → knitted report (ready to read).  
- `README.md` → this file.  

---

## Tools Used
- **R / RStudio** for cleaning, processing, and analysis.  
- **ggplot2, dplyr** for visualization and aggregation.  
- **RMarkdown** for reporting.  
