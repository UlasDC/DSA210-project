# DSA210 Term Project: The Effect of Weather Conditions on Goal Scoring in Beşiktaş Matches

## Motivation
Football matches are played under many different environmental conditions, and weather may influence the flow and outcome of a game. Rain, temperature, and wind can affect player performance, match tempo, and scoring opportunities. In this project, I aim to examine whether weather conditions have a measurable effect on the number of goals scored in Beşiktaş matches.

The project focuses on Beşiktaş matches over recent seasons and investigates whether variables such as precipitation, temperature, and wind speed are related to total goals scored in a match.

## Project Question
Does weather have a significant effect on the number of goals scored in Beşiktaş matches?

## Hypothesis
**Null Hypothesis (H₀):** Weather conditions do not significantly affect the total number of goals scored in Beşiktaş matches.

**Alternative Hypothesis (H₁):** Weather conditions significantly affect the total number of goals scored in Beşiktaş matches.

## Data Sources
This project combines two different datasets:

### 1. Match Data
Match data for Beşiktaş will be collected from publicly available football statistics sources such as:
- FBref
- Football-Data.co.uk

The match dataset is planned to include:
- Match date
- Opponent
- Home/Away information
- Final score
- Total goals in the match

### 2. Weather Data
Historical weather data will be collected using the Open-Meteo API.

The weather dataset is planned to include:
- Temperature
- Precipitation / rain
- Wind speed

Weather data will be matched to each match based on:
- Date
- Approximate kickoff time
- Match location

## Expected Dataset Size
The project is expected to cover approximately the last 5 to 10 seasons of Beşiktaş matches, depending on data availability and consistency.

Since a season contains around 34 to 40 league matches, the final dataset is expected to contain roughly 170 to 400 matches.

## Data Enrichment
The match dataset will be enriched by adding weather information for each match day. Additional derived variables may also be created, such as:
- Rainy vs non-rainy match indicator
- Temperature category
- Wind category

These features will help make the analysis more structured and interpretable.

## Methodology
The project will follow these steps:

1. Collect Beşiktaş match data from public football data sources.
2. Collect historical weather data for the same dates and locations.
3. Merge the match and weather datasets.
4. Clean the combined dataset and handle missing values if necessary.
5. Perform exploratory data analysis (EDA).
6. Conduct hypothesis testing.
7. Apply basic machine learning or regression methods if appropriate.

## Exploratory Data Analysis
The EDA stage will include:
- Summary statistics of match goals and weather variables
- Distribution plots for goals and weather conditions
- Comparisons of goals in rainy and non-rainy matches
- Scatter plots and correlation analysis between weather variables and total goals

## Hypothesis Testing
To test the main hypothesis, I plan to compare match goal counts under different weather conditions.

Possible methods include:
- Independent samples t-test
- Correlation analysis

The exact method will depend on the distribution and structure of the final dataset.

## Machine Learning / Modeling
If the dataset size and quality are sufficient, the project may also include simple predictive models such as:
- Linear Regression
- Decision Tree Regression
- Random Forest Regression

These models may help estimate whether weather variables contribute to predicting total goals in a match.

## Limitations
This project has some limitations:
- Weather is only one of many factors affecting football matches.
- Some older match records may have incomplete metadata.
- Stadium-level weather may sometimes be approximated using city-level data.
- The project focuses only on Beşiktaş matches, so findings may not generalize to all teams.

## Expected Outcome
The project aims to determine whether there is a meaningful relationship between weather conditions and goal scoring in Beşiktaş matches. Even if no strong statistical relationship is found, the project will still provide a useful data-driven examination of how environmental conditions may relate to football outcomes.

## Repository Contents
This repository is planned to include:
- Data collection notebooks/scripts
- Cleaned datasets
- Exploratory data analysis
- Hypothesis testing
- Modeling notebooks
- Final report
- README and reproduction instructions

## Notes
This project is being developed as part of the DSA210 Introduction to Data Science course.
