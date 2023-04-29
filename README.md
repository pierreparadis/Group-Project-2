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
**_Question 1: Do average happiness and average life expectancy have a strong correlation to average GDP and what socioeconomic factors may influence this?_**

Our team thought this was an interesting question because it examines the intersection of three important indicators of well-being: life expectancy, happiness, and GDP per capita. By identifying the countries that rank high in all three areas, we can gain insights into how economic development, social factors, and quality of life are interrelated, and what policies or practices these countries may have implemented to achieve such positive outcomes.

**_Question 2: What potential political, social, or economic events may have led to Honduras being ranked much lower in average happiness during the years 2015-2017 in contrast to surrounding countries?_**



## Manipulations 

For our dataset, we firstly adjusted many of the column names to be more clear indicators of their values. For example, we changed the “Economy” column to “GDP Per Capita” because that is the true value being used. We also removed data from 2019 and 2020 because they use different variables, making it difficult to correctly analyze. For our first visualization, we created a filter to only include European countries on our scatterplot since they have the most variance in happiness levels (they have some of the happiest and least happy countries in our dataset). For our second visualization, we created a filter to only show Central, South American, and Caribbean countries in order to focus in on distinctions within that particular region because there is a wide variety of social, political, and economic situations going on in those regions, and the heatmap allows us to narrow down our research into specific countries within said regions. When solving for average happiness rank among all countries in contrast to Honduras, we decided to exclude Haiti and Dominican Republic because they are 1. in the Caribbean and 2. outliers that could skew our analysis.



## Analysis and Results:

1. We chose to analyze the region of Europe for this question because of their wide range of happiness scores. There were countries such as Denmark, Switzerland, and Norway that averaged happiness ranks of 2, 2.3, and 3 respectively. Along with countries like Georgia, Armenia, and Bulgaria that were ranked 127, 123, and 122.7 in the same category. We found that yes, a positively correlated relationship exists between happiness score and average life expectancy in Europe. The average GDP per capita also plays a role in this, increasing with the trend line of the graph. The p-value of the trend line for the model including average life expectancy was < .0001 proving the model was statistically significant. Georgia, a country with a happiness score of 4.278 had an average life expectancy of .6731. Comparing this to Switzerland who scored 7.530 and .8875 respectively, you can see the strong correlation of the data. Georgia also had an average GDP per capita of .843 which was much smaller than that of Switzerland’s at 1.496. A big reason for these differences in many of the variables while both countries are in the same region can be attributed to conflicts in their close borders. Switzerland, has long and famously been a neutral and peaceful country avoiding many conflicts in its area. Two other countries at the top of the happiness score in the region, Denmark and Norway, have also been uninvolved in large conflicts in recent years. Looking towards Georgia, you can see the issues conflict and instability create. Georgia was involved in a the Russo-Georgian war in 2008 and is also shares a border with both Armenia and Azerbaijan who have actively been involved in an ongoing conflict for years. Both of those countries, also fall low on the happiness scale and this trend of conflict and unhappiness carries over to different subregions including Ukraine who was invaded by Russia in 2014, (our data is from 2015-2017 preceding the full on invasion of Ukraine) and the Balkan nations who have had numerous conflicts and turmoils since the breakup of Yugoslavia. Both Ukraine and many of the Balkan nations have lower happiness scores as well. Images are attached below to illustrate the locations of countries mentioned. In conclusion, we can strongly say that a relationship exists between average happiness score and average life expectancy while accounting for average GDP per capita in European countries.


<img width="771" alt="image" src="https://user-images.githubusercontent.com/128631042/235273246-cd00812b-fe8c-4487-b99d-6887326715a1.png">

2. Our group decided to focus in on countries in Central, South America, and the Caribbean because the large majority of countries in these regions have very similar happiness ranks - especially in Central and South America - but there is a clear outlier in the visualization, which is Honduras at an average rank of 100. Meanwhile, the rest of countries within the filter have an average happiness rank of 34.7 when you exclude the other outliers (in the Caribbean) of Haiti and the Dominican Republic. With such a glaring difference in happiness rank compared to its neighbors, we conducted research into potential factors leading to this disparity. 
	Firstly, In 2015, President Juan Orlando Hernandez announced that he would seek re-election in violation of the Honduran Constitution. This move was met with widespread opposition, as many Hondurans believed it was an attempt to consolidate power and undermine democracy. The Supreme Court of Honduras, which was packed with Hernandez's supporters, ruled in favor of his re-election, sparking protests and unrest across the country. Also, corruption has long been a problem in Honduras, with the country consistently ranking poorly on global corruption indices. In 2015, a corruption scandal involving the country's Social Security Institute (IHSS) came to light, revealing that over $300 million had been embezzled from the organization. The scandal implicated top government officials, including Hernandez's own sister, and sparked protests calling for an end to corruption and impunity. Finally, Honduras ranked as of the poorest countries in Latin America between the years 2015-2017, with high levels of inequality and unemployment. 
	As a result of this research, we have concluded that the disparity in average happiness rank during this time period can be attributed to mainly internal issues within Honduras - instead of widespread or regional issues. The social and political conflict from within have had an extremely detrimental impact on Honduran citizens, and the issues do not seem to have spread out to neighboring countries because all of Honduras’ bordering countries have an average combined happiness rank of 45.4 during these 3 years. It also explains why Honduras has experienced such massive emigration across Guatelama into Mexico - which has an average happiness rank of 20. 

<img width="711" alt="image" src="https://user-images.githubusercontent.com/128631042/235277297-efcd73d5-e549-42b0-b2d5-2aa222c2425d.png">




**Citations:**

Chivers, C. J. (2008, August 10). Georgia Says Russia Bombed Its Air Bases. The New York Times. https://www.nytimes.com/2008/08/11/world/europe/11georgia.html

Eurasianet. (2020). Azerbaijan-Armenia conflict. https://eurasianet.org/azerbaijan-armenia-conflict

International Federation of Red Cross and Red Crescent Societies. “Honduras, Central America & Mexico: Migration Crisis - Emergency Appeal n° MDR43008 - Country Operational Strategy.” ReliefWeb, 20 Nov. 2020, https://reliefweb.int/report/honduras/honduras-central-america-mexico-migration-crisis-emergency-appeal-no-mdr43008-country-operational-strategy.

Kurmanaev, Anatoly, and Kirk Semple. “Honduran President Declared Election Winner, but O.A.S. Calls for New Vote.” The New York Times, The New York Times, 13 Dec. 2017, https://www.nytimes.com/2017/12/13/world/americas/honduras-election-juan-orlando-hernandez.html.

Lakhani, Nina. “Honduras Protests over Social Security Embezzlement Scandal.” The Guardian, Guardian News and Media, 1 June 2015, https://www.theguardian.com/world/2015/jun/01/honduras-protests-social-security-embezzlement.

Transparency International. “Corruption Perceptions Index 2017.” Transparency International, 2017, https://www.transparency.org/en/cpi/2017/index/nzl.

World Bank. “Honduras Overview.” The World Bank Group, 2021, https://www.worldbank.org/en/country/honduras/overview.



**Tableau Packaged Workbook File:**

[GroupProject2.zip](https://github.com/pierreparadis/Group-Project-2/files/11358021/GroupProject2.zip)

