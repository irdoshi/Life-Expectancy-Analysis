# Life-Expectancy-Analysis

- The dataset was loaded and cleaned, removing cases with missing values for life expectancy, year, country name, and code.
- The dataset contained information for 203 unique countries.
- The earliest year with valid life expectancy data was 1800, and the most recent year was 2019.
- The lowest life expectancy value was observed in Cambodia in 1977, coinciding with a tragic genocide resulting in the loss of 1.5 to 2 million lives.
- The highest life expectancy value was found in San Marino in 2012.
- A line plot was created to visualize the life expectancy trend over time for all countries.
- Specific countries such as the United States of America, Korea, Republic of, Cambodia, China, and Rwanda were highlighted in the plot.
- Overall, life expectancy has been increasing over the years, possibly due to factors like improved healthcare, hygiene, lifestyle, diet, and medical care.
- However, significant dips in life expectancy were observed for Cambodia and Rwanda during periods of genocide and tragic killings.
- There is an inverse relationship between life expectancy and fertility rates, with increasing life expectancy corresponding to decreasing fertility rates.
- This trend may be influenced by factors such as women's empowerment, lower child mortality rates, and the rising cost of raising children.
- A histogram was used to visualize the distribution of life expectancy values, which appeared slightly left-skewed.
- Regression modeling was performed using the year (mod_year) as the predictor, revealing an intercept of 67.40 and a coefficient of 0.30 for the year parameter.
- Multiple regression analysis was conducted, adding the "region" (continent) variable to the model.
- The time trend was found to be statistically significant, indicating a significant impact of time on life expectancy.
- Additional variables, such as the log of GDP per capita and fertility rate, were included in an extended model, resulting in improved performance.
- The ranking of continents based on their impact on life expectancy changed, with the Americas leading, followed by Asia, Oceania, and Europe.
T- he Americas had the highest life expectancy based on the most recent model, followed by Asia, Oceania, and Europe.
