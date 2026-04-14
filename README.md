# DSA210 Term Project: Weather Impact on Turkish Super Lig Matches

## 📌 Motivation
Football is fundamentally shaped by environmental factors as much as tactical decisions. The motivation behind this project is to analyze how different weather conditions (such as heavy precipitation, strong winds, or extreme heat) influence in-match statistics and tactical approaches specifically within the **Turkish Super Lig**. For instance, does a rainy away game significantly decrease short passing accuracy? Does extreme heat lead to an increase in fouls due to fatigue? This project aims to uncover these hidden patterns using data science methodologies.

## 🗂️ Data Sources
To strictly satisfy the project's data enrichment requirement, two distinct datasets will be collected and merged:
1. **Match Statistics (Main Data):** Detailed in-match statistics for the Turkish Super Lig (e.g., passing accuracy, total goals, fouls, ball possession, aerial duels) will be collected using sources like **FBref** or **Football-Data.co.uk**.
2. **Weather Data (Enrichment):** Historical, hourly weather data (temperature, precipitation mm, wind speed) matching the exact kickoff time and cities of each Super Lig match will be fetched using the **Open-Meteo API**.

## ⚙️ Planned Data Pipeline
- **Data Collection & Preprocessing:** Scraping/downloading Super Lig match data and joining it with API-fetched weather data based on geographical coordinates and precise timestamps.
- **Exploratory Data Analysis (EDA):** Visualizing the correlations between weather elements and tactical match statistics (e.g., plotting precipitation levels against average passing accuracy).
- **Hypothesis Testing:** Performing statistical tests (e.g., T-tests) to determine if weather variations cause a statistically significant shift in gameplay style.
- **Machine Learning:** Building predictive models (e.g., Random Forest, Regression) to forecast specific match metrics or play styles based purely on the weather forecast and team characteristics.

---
*This repository is created for the DSA 210 Introduction to Data Science course (2025-2026 Spring Term).*