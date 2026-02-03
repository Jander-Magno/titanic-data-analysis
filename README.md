# Titanic Project - Data Analysis

This project analyzes Titanic passenger data to discover which factors influenced survival rates.

## Visualizations
![Survival Rate](survival_chart.png)
![Fare and survival](fare_boxplot.png)

## Key Insights
- **Gender:** Women had a significantly higher survival rate.
- **Age:** Children (under 12 years old) had a ~57% survival rate compared to ~36% for adults.
- **Socio-economic Status:** Social class was a determining factor: the higher the class, the higher the chance of being saved.
- **Gender as a Primary Factor:** Gender was the most significant predictor of survival. The data confirms the "Women and Children First" protocol, as female passengers had a drastically higher survival probability compared to males across all passenger classes.
- **The Price of Survival (Fare & Class):** Socioeconomic status was a decisive factor. The Fare Boxplot reveals that survivors generally paid higher ticket prices. Passengers in the lower fare brackets (primarily 3rd Class) faced the highest mortality rates, likely due to cabin locations and evacuation priority.
- **Predictive Power:** Our Machine Learning model reached an accuracy of 77.65%. This demonstrates that features like Gender, Class, and Fare provide a strong signal for predicting survival outcomes, although some "edge cases" remain difficult to categorize based on these variables alone.
- **Age and Family:** Preliminary analysis suggests that younger passengers and those traveling in small family units had a slight advantage, showing that family coordination and age-based priority influenced the final outcome.
