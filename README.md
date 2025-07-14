
# Fast Food Marketing Campaign A/B Test

## 📊 Project Overview
This project analyzes the effectiveness of three different marketing campaigns (Promotions 1, 2, and 3) conducted by a fast food chain. The goal is to determine which campaign led to the highest total sales per location using A/B testing and statistical analysis.

## 🗂️ Dataset
The dataset is sourced from the `wa_marketing_campaign` table in the `turing_data_analytics` BigQuery project. It contains weekly aggregated sales data by `LocationID` and `PromotionID`.

## 🎯 Objective
To identify the best-performing marketing campaign based on total sales per location, and provide actionable recommendations for future rollouts.

## 🧪 Methodology
- Data aggregation by `LocationID` and `PromotionID`
- Statistical analysis using:
  - ANOVA (Analysis of Variance)
  - Tukey HSD Test
  - Independent Samples t-test
- Confidence level: **99%** (to mitigate multiple testing problem)

## 📈 Results Summary
- Promotion 3 showed the highest average sales per location.
- Statistically significant differences were found between promotions.
- Recommendation: **Roll out Promotion 3** for future campaigns.

## 🛠️ Tools Used
- SQL (BigQuery)
- Google Sheets (for statistical tests and visualizations)
- Google Docs (for full report)

## 📎 Project Files
- https://docs.google.com/document/d/1kWH5xz2Hox526uNiF_Qq6seR_1hqPGnjnjR4BYY6vyo/edit?usp=sharing – Full report
- https://docs.google.com/spreadsheets/d/1smnA7Q4u6TEAXFauM19MiedDRvj5U2jwZw5Ubm18axw/edit?usp=sharing -  Prepared tables, chart and statistical tests (including ANOVA, Tukey HSD) used in report
- 📁 `SQL_Queries_M3S4.sql` – SQL queries used in the analysis

## 📬 Contact
For questions or feedback, feel free to reach out via GitHub or email.
