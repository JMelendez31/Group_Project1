# draft - project 1 write up

## Data Description
Through Kaggle.com, we accessed a World Health Organization dataset containing information on 179 countries from 2000 to 2015. Available variables incuded BMI, vaccination rates of different diseases, years of education, economy status (a dummy variable indicating the country as developed or developing), alcohol consumption, population, GDP per capita, and infant and adult mortality rates. The table below shows the summary statistics for the variables the group was most interested in. 

![image](https://github.com/JMelendez31/Group_Project1/assets/142682830/86ab74ae-e586-419f-99af-8f1f3bf2f909)


Following the summary statistics, our group identified the variables that we wanted to explore in relation to a country's average life expectancy. Using the economic status of the country, we decided to exploit the two groups to find those variables that have the strongest connection to life expectancy. Plotting the relationships between life expectancy in years with alcohol consumption, Body Mass Index, GDP per capita, and years of edcuation highlighted potential correlations of varying strength (dif word). From these visualizations, we moved to perform statistical tests to quantify these relationships. This included two ANOVA tests comparing regions with average life expectancies above and below 75 years and three t-tests between the lowest and highest life expectancy regions, lowest and second lowest regions, and highest and second highest regions. Finally, we performed a chi-square test on observed versus the expected life expectancy among regions. 

## Analysis and Conclusions
1. What are the key determinants affecting life expectancy?
- According to our visualizations, positive relationships exist between life expectancy and BMI, years of schooling, and there is a potential logarithmic relationship between life expectancy and GDP per capita.
- The p-values from four of our six tests indicated a statistically significant difference between life expectancies. Those are highlighted in the table below. This shows that there is a significant difference in life expectancy across the four quartiles of GDP ranges, and between those regions above and below 75 years of average life expectancy. (go more in depth on this)

2. How do these results change over time? (add to this section)
- using line plots, we showed that life expectancy, GDP per capita, and years of education have all increased over time, with GDP per capita having a more varied path likely due to economic crises or other external characteristics impacting growth. 
