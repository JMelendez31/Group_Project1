# project 1 write up

## Data Description
Through Kaggle.com, we accessed a World Health Organization dataset containing information on 179 countries from 2000 to 2015. Available variables included BMI, vaccination rates of different diseases, years of education, economic status (a dummy variable indicating the country as developed or developing), alcohol consumption, population, GDP per capita, and infant and adult mortality rates. The table below shows the summary statistics for the variables the group was most interested in. 

![image](https://github.com/JMelendez31/Group_Project1/assets/142682830/73aeee89-4292-48da-b3a7-46cbdd1b55e4)

Following the summary statistics, our group identified the variables that we wanted to explore in relation to a country's average life expectancy. Using the economic status of the country, we decided to exploit the two groups to find those variables that have the strongest connection to life expectancy. 

Plotting the relationships between life expectancy in years with alcohol consumption, Body Mass Index, GDP per capita, and years of education highlighted potential correlations of varying strength. From these visualizations, we moved to perform statistical tests to quantify these relationships. This included two ANOVA tests comparing regions with average life expectancies above and below 75 years and three t-tests between the lowest and highest life expectancy regions, lowest and second lowest regions, and highest and second highest regions. Finally, we performed a chi-square test on observed versus expected life expectancy among regions. We also investigated the changes seen over time by plotting a few variables for each region from 2000 to 2015. 

## Analysis and Conclusions
1. What are the key determinants affecting life expectancy?
- The p-values from five of our seven tests indicated a statistically significant difference between life expectancies. Those are shown in the table below. This meant that there was a significant difference in life expectancy across the four quartiles of GDP ranges and between those regions above and below 75 years of average life expectancy. The first row specifically shows that there is a statistically significant difference between the life expectancy of developed and developing nations, which gave us the justification to further explore what variables may be causing this difference.
![image](https://github.com/JMelendez31/Group_Project1/assets/142682830/9de8728c-a832-418d-8632-623fdcd937dc)
- According to our visualizations, positive relationships exist between life expectancy and BMI, and life expectancy and alcohol consumption. There is also a positive relationship with years of schooling, and a potential logarithmic relationship between life expectancy and GDP per capita. The relationships were strongest between life expectancy, GDP per capita, and years of schooling. This led us to believe that although there may be correlation between the other variables, the causal relationship was likely stronger with GDP and education. 

2. How do these results change over time?
- Using line plots, we showed that life expectancy, GDP per capita, and years of education have all increased over time, with GDP per capita having a more varied path likely due to economic crises or other external characteristics impacting growth.
- Looking at the GDP over time, we saw that a region like Africa did not experience similar rates of growth to their changing life expectancy. This indicated that the years of education may have been more of a determinant even than GDP per capita. 

Please see the PowerPoint file attached for our graphs and visualizations addressing each individual variable and the changes over time. 
