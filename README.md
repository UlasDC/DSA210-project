# DSA210 Term Project: Weather Impact on Turkish Super Lig Matches

## 📌 Motivation
Football is fundamentally shaped by environmental factors as much as tactical decisions. Playing a game at Erzurum in -30 C is not the same as playing at Antalya in 40 C.The motivation behind this project is to analyze how different weather conditions influence in-match statistics and tactical approaches specifically within the **Turkish Super Lig**. For instance, does a rainy away game significantly decrease total number of passes or overall passing accuracy? Does the increase in heat lead to an increase in fouls due to fatigue? This project aims to uncover these hidden patterns using data science methodologies.

## 🗂️ Data Sources
Two distinct datasets will be collected and merged:
1. **Match Statistics:** Detailed in-match statistics for the Turkish Super Lig (e.g., passing accuracy, total goals, fouls, ball possession, aerial duels) will be collected using sources like **FBref** or **Football-Data.co.uk**.
2. **Weather Data:** Historical, hourly weather data (temperature, wind speed) matching the exact kickoff time and locations of each Super Lig match will be fetched using the **Open-Meteo API**.
