# IMPACT OF FOOD PRICES ON HEALTH: COMPARING NIGERIA AND OTHER AFRICAN COUNTRIES (2017–2021).

![image.alt](https://github.com/Somagachukwu/IMPACT-OF-FOOD-PRICES-ON-HEALTH-COMPARING-NIGERIA-AND-OTHER-AFRICAN-COUNTRIES-2017-2021-./blob/main/Impact%20of%20health/IMPACT%20OF%20HEALTH.png)
# Introduction
### The relationship between food prices and health is a critical and complex issue with far-reaching consequences for individuals, communities, and societies at large. Food prices directly influence dietary choices, food security, and ultimately the health outcomes of populations around the world. As prices of essential and nutritious foods increase, particularly in economically vulnerable regions, people are often forced to make dietary compromises, leading to inadequate intake of essential nutrients, increased reliance on cheaper, highly processed foods, and an elevated risk of both malnutrition and chronic health conditions.
### Rising food prices can push households, especially low-income ones, to prioritize quantity over quality, opting for calorie-dense but nutrient-poor foods, such as refined grains, sugary snacks, and fast food. This dietary shift is strongly linked to a rise in obesity, diabetes, cardiovascular diseases, and other diet-related illnesses. The affordability of fruits, vegetables, whole grains, and lean proteins is essential for maintaining a balanced diet, yet these items are often among the first to become inaccessible when food prices rise. Meanwhile, the fluctuating prices of staple foods, such as grains and dairy, can cause households to either reduce their consumption or turn to cheaper, less nutritious substitutes, worsening food insecurity and the risk of nutrient deficiencies.
### The impact of food prices on health extends beyond individual households to influence broader social and economic outcomes. Poor health due to inadequate nutrition leads to lost productivity, higher healthcare costs, and reduced economic growth, creating a cycle of poverty and ill-health that is difficult to break. Governments and international organizations increasingly recognize the need to stabilize food prices, promote local agriculture, and subsidize healthy foods to ensure that all individuals have access to affordable, nutritious diets.

### This report presents an in-depth analysis of the impacts of food prices in health in Nigeria and three African countries from 2017–2021. The analysis aims to provide a holistic understanding of how food prices influence health and to suggest actionable solutions for enhancing food security and nutrition
### This analysis highlights not only the cost of healthy diets but also the health implications of not taking a healthy diet, the population that can afford a healthy diet, the prevalence of undernourishment, and its correlation with food prices.

## Objectives of These analyses

1. To examine the affordability of a healthy diet.
2. To analyse the prevalence of undernourishment and its correlation with food prices.
3. To identify key factors influencing high food prices.
4. To understand the health implications of unaffordable diets.
5. To provide evidence-based recommendations to policymakers and stakeholders to address high food prices, enhance diet affordability, and improve public health outcomes.

## Data Collection
### The datasets were provided by Amdor Analytics and was also obtained from world bank.

## Analysis Approach
### Whilst the requirement has been spelt out, the dataset was inspected to see if the available data was enough to provide the needed solution.
### The dataset contains 4 CSV file.
### The first CSV file contains the daily cost of a healthy diet per person, the second contains information on the monthly change in food prices over the years, the third contains information on the share of population that cannot afford a healthy meal, the fourth contains the information the share of population that is undernourished, and the fifth and last csvg file contains  contains information on the employment rate of the population.
## Methodology

## Data Manipulation
### Power query in Microsoft Power BI was used to clean this data set.
### The dataset underwent some processes like removing duplicates and blank rows in which none was found. The brief indicated that the analysis can be done on one country and also compare it against three neighboring countries, with this in mind the countries were filtered to Nigeria, Benin, Algeria and Ghana with Nigeria as the focus country. The datasets contained different years and the most common years across each dataset was 2017–2021, filtering each of the data set to this common year, analysis was only done across these years.

## Creating Relationship Between Each Table and Creating a Dimension Table.
### With that done, the datasets were inspected, and a relationship was created among them to enable easy analysis. The relationship between each table was a many-to-one relationship. A dimension table was also created for each dataset for Nigeria’s focus country.
![image.alt](https://github.com/Somagachukwu/IMPACT-OF-FOOD-PRICES-ON-HEALTH-COMPARING-NIGERIA-AND-OTHER-AFRICAN-COUNTRIES-2017-2021-./blob/main/Impact%20of%20health/impact%20of%20health%20modelling.png)

## Analysis
### After the modelling was done and all the necessary relationships established, the next stage is to start analysing the data and creating a beautiful dashboard that would show all key metrics and actionable insights that can easily be understood even by non-technical personnel.
### The dashboard consisted of three pages.
### The first Page displays a summary of the Nigeria’s report featuring Key Metrics such as:
* Total cost of a healthy diet: The total cost of a healthy diet from 2017–2021 in Nigeria
* Total prevalence of under nourishment: The prevalence rate of under nourishment.
* Issue: The distinct count of the issues of the complaint.
* Average cost of a healthy diet: The average cost of a healthy diet from 2017–2021 in Nigeria.
* Total Percent of population able to afford a healthy diet: The total percentage of population able to afford a healthy diet in Nigeria.
![image.alt](https://github.com/Somagachukwu/IMPACT-OF-FOOD-PRICES-ON-HEALTH-COMPARING-NIGERIA-AND-OTHER-AFRICAN-COUNTRIES-2017-2021-./blob/main/Impact%20of%20health/Impact%20of%20health%20pg%201.png)

### The second page displays a summary of the comparism between Nigeria, Ghana, Benin and Algeria
* Total cost of a healthy diet: The total cost of a healthy diet across each country
* Prevalence of under nourishment (%): The total percentage of under nourishment in the population across each country.
* Country: The total number of countries analysed.
![image.alt](https://github.com/Somagachukwu/IMPACT-OF-FOOD-PRICES-ON-HEALTH-COMPARING-NIGERIA-AND-OTHER-AFRICAN-COUNTRIES-2017-2021-./blob/main/Impact%20of%20health/Impact%20of%20health%20pg%202.png)

### The third is a continuation of the key metrics for the comparism such as:
* Obesity Rate (%): Percentage total of obesity across the countries.
* Hunger Prevalence: The total percent of the prevalence of hunger across the countries.
* Malnutrition Rate: The total percent of malnutrition across the countries.
* Diabetes Rate: shows the total percent of diabetes across the countries.
![image.alt](https://github.com/Somagachukwu/IMPACT-OF-FOOD-PRICES-ON-HEALTH-COMPARING-NIGERIA-AND-OTHER-AFRICAN-COUNTRIES-2017-2021-./blob/main/Impact%20of%20health/Impact%20of%20health%20pg%203.png)

## Observation
### The analysis exposed quite a few things that should be addressed in order reduce cost of food prices.
1. In Nigeria, 2021 had the highest cost of a healthy diet which was $4325 compared to 2017 with the least cost which was $3.625.
2. The health implications for these food prices was low across all years except in 2021 which recorded a 330% increase in hunger prevalence in Nigeria.
3. 2021 recorded the highest number of population that cannot afford a healthy diet with a record of 93.6%% and 2017 recording the least with a total percent of 90.2 in Nigeria.
4. In Nigeria, 2021 recorded the highest prevalence of under nourishment with a record of 15.90% compared to 2017 which recorded the least with a record of 10%.
5. Comparing Nigeria to Algeria, Ghana and Benin. Nigeria had the highest prevalence of under nourishment with a record of 15.90% and Benin following behind with a record of 9.90%. These two countries recorded the highest percentage of under nourishment across each year.
6. Nigeria and Benin recorded the highest percent of population unable to afford a healthy meal across each year while Algeria recorded the least percent.
7. Nigeria and Ghana recorded the highest costs of a healthy diet compared to Benin which had a record of the least cost of a healthy diet across each year.
8. Nigeria and Ghana had the highest percent of malnutrition across each year compared to Algeria which had the least.
9. Algeria and Ghana recorded high percents of diabetes across each year with Nigeria being the least.
10. Algeria and Ghana also recorded high rates of obesity compared to Nigeria being the least across each year.
11. Nigeria recorded the highest rate of employment in the agric sector across each years.
12. Algeria recorded the highest rate of employment in both the industry and service sector across all years

## Recommendations
Based on the above observations, here are my humble recommendations:
1. Enhance Agricultural Productivity and Efficiency
Invest in Agricultural Technology: Support the adoption of climate-resilient crops, improved irrigation systems, and sustainable farming practices to increase yields and reduce production costs.
Subsidize Inputs: Provide subsidies for seeds, fertilizers, and equipment to lower costs for farmers and stabilize food prices.
Reduce Post-Harvest Losses: Improve storage facilities, transportation, and processing to prevent waste and ensure food availability.
2. Strengthen Food Supply Chains
Streamline Logistics: Reduce bottlenecks in transportation and distribution networks to decrease food costs.
Promote Local Markets: Encourage the development of local food markets to reduce dependency on imports and transport-related costs.
Enhance Trade Policies: Support trade agreements that reduce tariffs and other barriers for essential food commodities.
3. Implement Social Safety Nets
Food Assistance Programs: Expand access to food vouchers, school meal programs, and cash transfers targeting vulnerable populations.
Subsidize Nutritious Foods: Lower the cost of healthy staples (e.g., fruits, vegetables, whole grains) to make them more accessible.
4. Support Healthy Food Environments
Tax Unhealthy Foods: Introduce taxes on sugary beverages and ultra-processed foods to discourage consumption and generate revenue for public health initiatives.
Subsidize Healthy Foods: Use revenues from these taxes to subsidize healthier options.
Strengthen Food Labeling: Mandate clear nutritional labeling to guide consumer choices.
5. Promote Urban and Community Agriculture
Support Urban Farming: Encourage small-scale gardening and urban agriculture to provide affordable, locally grown produce.
Incentivize Community Co-ops: Facilitate the formation of community cooperatives that can pool resources to produce and distribute healthy foods.
7. Address Underlying Socioeconomic Inequities
Living Wage Policies: Advocate for wages that enable families to afford a nutritious diet.
Strengthen Social Protection: Address income inequality to reduce economic barriers to accessing healthy food.
8. Invest in Research and Monitoring
Data-Driven Policies: Fund research to monitor food prices, dietary trends, and public health outcomes to guide interventions.
Pilot Programs: Test innovative approaches to improve diet affordability and scale successful initiatives.

### Stakeholder Collaboration
* Government: Develop and enforce policies that regulate food markets, trade, and agricultural practices.
* Private Sector: Partner with food producers and retailers to ensure affordable access to nutritious food.
* NGOs and Community Organizations: Support grassroots efforts to address food insecurity and promote healthy diets.
By implementing these strategies, policymakers and stakeholders can tackle high food prices, improve diet affordability, and sustainably achieve better public health outcomes.

## Conclusion
The analysis of the impact of food prices on health has provided valuable insights into the country’s food prices, undernutrition rate and share of population that cannot afford a healthy meal. The findings highlight areas of strength, such as the increase in employment rates in different sectors. However, the analysis also reveals opportunities for improvement such as optimizing the prices of food.
By implementing the recommendations outlined in this report, countries can enhance food production and reduce malnutrition rate and therefore produce a country with great productivity.

# Thank you for reading!
