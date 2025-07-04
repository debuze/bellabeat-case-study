# Bellabeat Case Study: How Can a Wellness Technology Company Play It Smart?

## Introduction

This is a case study for the Google Data Analytics Professional Certificate. The goal is to analyze smart device data to gain insight into how consumers are using their smart devices. The insights discovered will help guide marketing strategy for Bellabeat, a high-tech manufacturer of health-focused products for women.

### The Business Task:
Analyze smart device usage data to identify trends and provide recommendations for Bellabeat's marketing strategy.

### Key Stakeholders:
* Urška Sršen: Bellabeat's cofounder and Chief Creative Officer
* Sando Mur: Mathematician and Bellabeat's cofounder
* Bellabeat marketing analytics team

---

## 1. Ask

The primary business questions guiding this analysis are:
1.  What are some trends in smart device usage?
2.  How could these trends apply to Bellabeat customers?
3.  How could these trends help influence Bellabeat marketing strategy?

---

## 2. Prepare

### Data Source:
The data used is the **FitBit Fitness Tracker Data** from Kaggle (CC0: Public Domain). It's a public dataset generated by respondents to a distributed survey via Amazon Mechanical Turk, containing data from thirty Fitbit users.

### Data Organization and Verification:
The dataset is stored in 18 CSV files. I used R to explore the data, checking for missing values, duplicates, and errors. The data was found to be generally reliable, but the small sample size (30 users) is a limitation.

---

## 3. Process

### Tools Used:
* **R and RStudio:** For data cleaning, transformation, and analysis.
* **R Packages:** `tidyverse`, `lubridate`, `ggplot2`.

### Data Cleaning Steps:
* Checked for and removed duplicate entries.
* Formatted date and time columns for consistency.
* Merged multiple datasets (e.g., daily activity and sleep) into a single, comprehensive dataframe for analysis.
* Added new columns for deeper analysis, such as "DayOfWeek".

---

## 4. Analyze & 5. Share

Here are some of the key findings from the analysis.

### Finding 1: Users are Most Active in the Early Evening
This chart shows that activity peaks between 5 PM and 7 PM.

[![Chart showing activity by hour](path/to/your/chart1.png)](https://github.com/debuze/bellabeat-case-study/blob/main/chart1_activity_by_hour.png)

### Finding 2: A Strong Link Between Steps and Sleep
Users who take more steps also tend to get more sleep.

[![Chart showing steps vs sleep](path/to/your/chart2.png)](https://github.com/debuze/bellabeat-case-study/blob/main/chart2_sleep_vs_steps.png)

### Finding 3: Sedentary Time is High
A large portion of the day is spent sedentary, even for active users. This represents a key opportunity.

[![Chart showing sedentary minutes](path/to/your/chart3.png)](https://github.com/debuze/bellabeat-case-study/blob/main/chart3_steps_vs_sedentary.png)

---

## 6. Act: Recommendations for Bellabeat

Based on the analysis, here are three recommendations for Bellabeat's marketing team:

1.  **Focus on Mid-day Motivation:** Since users are most active in the evening, Bellabeat could create marketing campaigns and app notifications that encourage short, mid-day walks or activities to break up sedentary time.
2.  **Market Sleep Benefits:** Highlight how Bellabeat's sleep tracking features can help users improve their sleep, which is directly correlated with higher activity levels.
3.  **Launch Weekend Wellness Challenges:** Since activity patterns might differ on weekends, Bellabeat could use its app to launch fun challenges to keep users engaged and moving.

