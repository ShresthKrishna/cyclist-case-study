# 🚴‍♂️ Cyclistic Case Study: Converting Casual Riders to Annual Members

## 📘 Project Overview

This case study explores how annual members and casual riders use the Cyclistic bike-share system differently. The analysis is based on cleaned Q1 datasets from 2019 and 2020, prepared as part of the Google Data Analytics Capstone Project.

**Business Goal:**  
Understand how **casual riders** and **annual members** use Cyclistic bikes differently, with the objective of supporting a marketing strategy that encourages casual riders to purchase annual memberships.

**Tools Used:**  
- Excel (initial data validation and cleaning)  
- R (tidyverse, ggplot2, dplyr)  
- GitHub (project documentation and portfolio sharing)

---

## 🔍 Prepare Phase

### 📌 Data Source  
- Downloaded from [Divvy Trip Data Repository](https://divvy-tripdata.s3.amazonaws.com/index.html)
- Datasets used: `2019 Q1`, `2020 Q1`, and later extended to all of 2019

### 📁 Data Organization  
- Cleaned in Excel and R  
- Columns such as `ride_length`, `day_of_week`, `age_group`, and `usertype` standardized

### 🧠 Data Integrity Checks  
- Removed invalid entries (e.g., end_time before start_time, ride > 24 hrs)  
- Handled missing values (e.g., `gender`, `birthyear` → replaced with `"Unknown"`)

---

## 🔎 Process Phase

- Combined Q1–Q4 of 2019 for complete seasonal analysis  
- Standardized formats and fixed inconsistencies  
- Verified structure and sanity of columns (e.g., converted ride length to numeric minutes)

---

## 📊 Analyze Phase

### Descriptive Statistics  
- Casual riders take **fewer rides**, but **longer durations**  
- Members ride **more frequently**, especially on weekdays

### Behavioral Patterns  
- Members mostly ride during weekdays (likely for commuting)  
- Casual riders are more active on weekends (likely recreational use)

---

## 📈 Share Phase

### Key Visualizations:
- Bar charts: Ride frequency by weekday and user type  
- Line charts: Average ride duration over days  
- Box plots: Duration spread across user types  
- Age + weekday usage: Which demographics ride when

### Communication Strategy:
- Target casual riders with weekend discounts and day-pass upsells  
- Promote benefits of membership based on usage frequency and cost savings

---

## 🚀 Act Phase

### Top 3 Recommendations:
1. Launch **weekend-focused membership trials** to convert casual users  
2. Highlight **long-ride savings** and add-ons in casual user marketing  
3. Use ride data to **tailor campaigns by age group and time preference**

---
