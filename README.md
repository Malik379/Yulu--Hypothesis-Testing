# Yulu-Demand_Analysis
### About Yulu
Yulu is India’s leading micro-mobility service provider, offering unique vehicles for daily commutes. Starting as a mission to eliminate traffic congestion in India, Yulu provides the safest commute solutions through a user-friendly mobile app, enabling shared, solo, and sustainable commuting. Yulu zones are strategically located at metro stations, bus stands, office spaces, residential areas, corporate offices, and more to make first and last miles smooth, affordable, and convenient.

### Business Problem
Yulu has recently experienced significant dips in revenue and has contracted a consulting company to understand the factors influencing the demand for their shared electric cycles in the Indian market. The objectives are to identify significant variables predicting demand and to assess how well these variables describe electric cycle demand.

### Dataset Information
The dataset contains information on various factors that might affect the demand for shared electric cycles. The features included are:
datetime: Datetime

season: Season (1: spring, 2: summer, 3: fall, 4: winter)

holiday: Whether the day is a holiday or not

workingday: If the day is neither weekend nor holiday is 1, otherwise 0

weather:

1: Clear, Few clouds, partly cloudy

2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist

3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds

4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog

temp: Temperature in Celsius

atemp: Feeling temperature in Celsius

humidity: Humidity

windspeed: Wind speed

casual: Count of casual users

registered: Count of registered users

count: Count of total rental bikes including both casual and registered

Dataset Link:"https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/428/original/bike_sharing.csv?1642089089"

## Analysis Tasks
Data Import and Initial Exploration

Load and inspect the dataset's structure and characteristics.

Detect and handle missing values and outliers.

Data Profiling and Visualization

Create demographic profiles of customers.

Visualize spending patterns using histograms, box plots, and scatter plots.

## Statistical Analysis
Perform Bi-Variate Analysis.

Conduct 2-sample t-tests to check for differences across populations.

Conduct ANOVA to check for differences in the number of cycles rented across seasons and weather conditions.

Conduct Chi-square tests to check if weather is dependent on the season.

## Hypothesis Testing
Set up Null Hypothesis (H0) and Alternate Hypothesis (H1).

Check assumptions of the tests (Normality, Equal Variance).

Set a significance level (alpha).

Calculate test statistics.

Make a decision to accept or reject the null hypothesis.

Draw inferences from the analysis.

## Insights and Recommendations
Summarize key findings and provide actionable recommendations for Yulu to optimize operations and marketing strategies based on the analysis results.
