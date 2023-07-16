# Life-Expectancy-Analysis

- Loaded and cleaned the dataset, removing cases with missing values for life expectancy, year, country name, and code.
- The dataset contained information for 203 unique countries. The earliest year with valid life expectancy data was 1800, and the most recent year was 2019.
- Found that Cambodia had the lowest life expectancy value in 1977, which coincided with a tragic genocide resulting in the loss of 1.5 to 2 million lives.
- On the other hand, San Marino had the highest life expectancy value in 2012.
- Created a line plot to visualize the life expectancy trend over time for all countries.
- Highlighted countries such as the United States of America, Korea, Republic of, Cambodia, China, and Rwanda in the plot.
- Observed that life expectancy has been increasing over the years, possibly due to factors like improved healthcare, hygiene, lifestyle, diet, and medical care.
- Noticed significant dips in life expectancy for Cambodia and Rwanda during periods of genocide and tragic killings.
- Found an inverse relationship between life expectancy and fertility rates, with increasing life expectancy corresponding to decreasing fertility rates.
- This trend may be influenced by factors such as women's empowerment, lower child mortality rates, and the rising cost of raising children.
- Used a histogram to visualize the distribution of life expectancy values, which appeared slightly left-skewed.
- For regression modeling, I used the year (mod_year) as the predictor, which revealed an intercept of 67.40 and a coefficient of 0.30 for the year parameter.
- Conducted multiple regression analysis by adding the "region" (continent) variable to the model.
- Found that the time trend was statistically significant, indicating a significant impact of time on life expectancy.
- In an extended model, I included additional variables such as the log of GDP per capita and fertility rate, which resulted in improved performance.
- The ranking of continents based on their impact on life expectancy changed, with the Americas leading, followed by Asia, Oceania, and Europe.
- Based on the most recent model, Americas had the highest life expectancy, followed by Asia, Oceania, and Europe.
