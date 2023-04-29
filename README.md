# Group-Project-2

Team Name: 21482_3

     
Team Members 

- Lily Fitzgerald  [@lilyjfitz](https://github.com/lilyjfitz)
- Pierre Paradis [@pierreparadis](https://github.com/pierreparadis)
- Ethan Delamater  [@ethandelamater](https://github.com/ethandelamater)
- Anders Roth [@AndersRoth](https://github.com/AndersRoth)
- Joseph Fredeman [@Jfredeman](https://github.com/Jfredeman)





## Data Set Description

Our dataset was obtained from Kaggle, an online data science community with various open datasets to choose from. Our dataset is the “World Happiness Report” formed by the Sustainable Development Network. In the dataset, there are 10 columns: Year, Country, Happiness Rank (from 1-158), Happiness Score, GDP Per Capita, Family, Life Expectancy, Freedom, Government Corruption, and Generosity. Data types include integer and string types - the only string being the Country name. In total, there are 471 rows in the dataset, however, this is a combination of between 155-158 rows for each year from 2015-2017. The values for columns (aside from Happiness Score) are ratios between 0 and 1, with 1 being the best - or worst for government corruption - possible score. 
 
## Our Questions
_Question 1: Do average happiness and average life expectancy have a strong correlation to average GDP and what socioeconomic factors may influence this?_

Our team thought this was an interesting question because it examines the intersection of three important indicators of well-being: life expectancy, happiness, and GDP per capita. By identifying the countries that rank high in all three areas, we can gain insights into how economic development, social factors, and quality of life are interrelated, and what policies or practices these countries may have implemented to achieve such positive outcomes.

_Question 2: _



## Manipulations 

For our dataset, we firstly adjusted many of the column names to be more clear indicators of their values. For example, we changed the “Economy” column to “GDP Per Capita” because that is the true value being used. We also removed data from 2019 and 2020 because they use different variables, making it difficult to correctly analyze. For our first visualization, we created a filter to only include European countries on our scatterplot since they have the most variance in happiness levels (they have some of the happiest and least happy countries in our dataset). For our second visualization, we created a filter to only show Central and South American countries in order to focus in on distinctions within that particular region because there is a wide variety of social, political, and economic situations going on in those regions, and the heatmap allows us to narrow down our research into specific countries within said regions. 



## Analysis and Results:

1. We chose to analyze the region of Europe for this question because of their wide range of happiness scores. There were countries such as Denmark, Switzerland, and Norway that averaged happiness ranks of 2, 2.3, and 3 respectively. Along with countries like Georgia, Armenia, and Bulgaria that were ranked 127, 123, and 122.7 in the same category. We found that yes, a positively correlated relationship exists between happiness score and average life expectancy in Europe. The average GDP per capita also plays a role in this, increasing with the trend line of the graph. The p-value of the trend line for the model including average life expectancy was < .0001 proving the model was statistically significant. Georgia, a country with a happiness score of 4.278 had an average life expectancy of .6731. Comparing this to Switzerland who scored 7.530 and .8875 respectively, you can see the strong correlation of the data. Georgia also had an average GDP per capita of .843 which was much smaller than that of Switzerland’s at 1.496. A big reason for these differences in many of the variables while both countries are in the same region can be attributed to conflicts in their close borders. Switzerland, has long and famously been a neutral and peaceful country avoiding many conflicts in its area. Two other countries at the top of the happiness score in the region, Denmark and Norway, have also been uninvolved in large conflicts in recent years. Looking towards Georgia, you can see the issues conflict and instability create. Georgia was involved in a the Russo-Georgian war in 2008 and is also shares a border with both Armenia and Azerbaijan who have actively been involved in an ongoing conflict for years. Both of those countries, also fall low on the happiness scale and this trend of conflict and unhappiness carries over to different subregions including Ukraine who was invaded by Russia in 2014, (our data is from 2015-2017 preceding the full on invasion of Ukraine) and the Balkan nations who have had numerous conflicts and turmoils since the breakup of Yugoslavia. Both Ukraine and many of the Balkan nations have lower happiness scores as well. Images are attached below to illustrate the locations of countries mentioned. In conclusion, we can strongly say that a relationship exists between average happiness score and average life expectancy while accounting for average GDP per capita in European countries.


<img width="571" alt="image" src="https://user-images.githubusercontent.com/128631042/235273246-cd00812b-fe8c-4487-b99d-6887326715a1.png">








Citations:

Chivers, C. J. (2008, August 10). Georgia Says Russia Bombed Its Air Bases. The New York Times. https://www.nytimes.com/2008/08/11/world/europe/11georgia.html

Eurasianet. (2020). Azerbaijan-Armenia conflict. https://eurasianet.org/azerbaijan-armenia-conflict


[GroupProject2.zip](https://github.com/pierreparadis/Group-Project-2/files/11357968/GroupProject2.zip)

