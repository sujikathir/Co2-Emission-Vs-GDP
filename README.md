# World Development Indicators: Co2-Emission-Vs-GDP

![](https://github.com/sujikathir/Co2-Emission-Vs-GDP/blob/main/images/main%20image.png)

This project dives into the World Development Indicators dataset from the World Bank, with a particular emphasis on visualizing CO2 emissions per capita. The goal is to analyze and understand trends, distributions, and insights regarding global CO2 emissions. Through compelling visualizations using Python's powerful Matplotlib library, this project transforms complex data into easily understandable graphics.

## Dataset

The World Development Indicators dataset is a comprehensive collection of various indicators for different countries, spanning from 1960 to 2015. The dataset includes *5,656,458* rows and 6 columns, providing extensive coverage of global development metrics:

- CountryName: The name of the country.

- CountryCode: The ISO 3166-1 alpha-3 country code.

- IndicatorName: The name of the indicator.

- IndicatorCode: The code representing the indicator.

- Year: The year of the data point.

- Value: The value of the indicator for that specific year.

## Why This Project?
### Importance of CO2 Emissions Data

![](https://github.com/sujikathir/Co2-Emission-Vs-GDP/blob/main/images/1.1.%20Top%20Co2%20emitting%20countries.jpg)

CO2 emissions are at the forefront of global environmental concerns due to their significant impact on climate change. As of recent years, the global community faces a pressing need to reduce CO2 emissions to mitigate the adverse effects of climate change, such as extreme weather events, rising sea levels, and disruptions to ecosystems and biodiversity. Understanding CO2 emissions on a per capita basis is crucial for several reasons:

- Policy Making: Governments need accurate data to create effective environmental policies and regulations. By visualizing CO2 emissions data, policymakers can identify trends, set targets, and track progress over time.

- Public Awareness: Raising awareness about CO2 emissions helps the public understand their role in climate change. This project translates complex data into clear visuals, making it accessible to a broader audience.

- International Comparisons: Comparing emissions across countries can highlight best practices and areas needing improvement. It fosters international cooperation in addressing global environmental challenges.

- Business Strategy: Companies can use emissions data to align their strategies with sustainability goals. Understanding national and global trends can inform better business decisions and promote corporate responsibility.

- Academic Research: Researchers can use the visualized data to support studies on environmental science, economics, and social sciences, contributing to a deeper understanding of the factors driving CO2 emissions.

## The Current Situation of CO2 Emissions

### 1. Global Trends and Concerns

![](https://github.com/sujikathir/Co2-Emission-Vs-GDP/blob/main/images/1.2.%20Past%203%20global%20carbon%20budget.png)

- Rising Emissions: Despite efforts to curb emissions, global CO2 levels have continued to rise, driven primarily by industrial activities, transportation, and energy production.

- Regional Disparities: Emissions vary significantly across regions, with developed countries historically contributing more per capita compared to developing nations.

![](https://github.com/sujikathir/Co2-Emission-Vs-GDP/blob/main/images/1.3.%20Carbon%20cycle%20-%20Ocean.png)

- Impact on Climate: CO2 is a greenhouse gas that traps heat in the atmosphere, leading to a warming planet. This has far-reaching consequences for global weather patterns, agriculture, and human health.

### 2. Environmental Impacts

![](https://github.com/sujikathir/Co2-Emission-Vs-GDP/blob/main/images/1.5.%20Damage%20to%20ocean.jpg)

- Sea Level Rise: As temperatures increase, polar ice caps and glaciers melt, causing sea levels to rise. This threatens coastal communities and ecosystems worldwide.

- Extreme Weather: Increased CO2 levels contribute to more frequent and severe weather events, such as hurricanes, droughts, and heatwaves, impacting millions of people annually.

- Ecosystem Disruption: Changes in climate disrupt ecosystems, endangering species and reducing biodiversity, which is vital for ecological balance and human livelihoods.

### 3. Policy and International Commitments

- Paris Agreement: The international community, through the Paris Agreement, aims to limit global temperature rise to well below 2 degrees Celsius above pre-industrial levels. This necessitates substantial reductions in CO2 emissions.

- National Policies: Many countries have implemented policies and regulations to reduce emissions, promote renewable energy sources, and improve energy efficiency. These efforts are critical for achieving climate targets and sustainable development goals.
  
  
![](https://github.com/sujikathir/Co2-Emission-Vs-GDP/blob/main/images/1.4.%20projected%20target.png)



![](https://github.com/sujikathir/Co2-Emission-Vs-GDP/blob/main/images/1.6.%20Policies%20and%20pledges.png)


## Tools and Libraries used in this project

This project utilizes several powerful tools and libraries to perform data analysis and visualization:

- Python: The core programming language for data analysis and visualization.

- Pandas: For data manipulation and analysis, providing data structures and operations to manipulate numerical tables and time series.

- NumPy: For numerical computing, providing support for arrays and matrices.

- Matplotlib: For creating static, interactive, and animated visualizations in Python.

- Google Colab: For writing and executing the notebook in an interactive environment.

- Kaggle: As the source of the dataset.

## Key Steps and Findings

1. Initial Exploration

   ![](https://github.com/sujikathir/Co2-Emission-Vs-GDP/blob/main/images/1.%20graph.png)

- Unique Countries: The dataset includes data for 247 unique countries.

- Unique Indicators: There are 1,344 unique indicators in the dataset.

- Years Covered: The dataset covers a period from 1960 to 2015, spanning 56 years.

2. Detailed Analysis: CO2 Emissions in the USA

To delve deeper, I focused on the "CO2 emissions (metric tons per capita)" indicator for the USA. This analysis helps understand how CO2 emissions per capita have changed over time in one of the world's largest economies.

1. CO2 Emissions Over Time (1960-2011)

Visualization: A line plot showcasing CO2 emissions per capita over the years.

![](https://github.com/sujikathir/Co2-Emission-Vs-GDP/blob/main/images/2.%20graph%20Co2%20Emission%20in%20USA.png)

Observation: The trend reveals fluctuations, with periods of both increase and decrease in emissions.

2. Distribution of CO2 Emissions

Visualization: A histogram illustrating the distribution of CO2 emissions per capita over the years.

![](https://github.com/sujikathir/Co2-Emission-Vs-GDP/blob/main/images/3.%20histogram.png)

Observation: The majority of the years have emissions concentrated between 19-20 metric tons per capita, with outliers on either side.

### Comparative Analysis: CO2 Emissions in 2011

Extending the analysis, I compared CO2 emissions per capita across all countries for the year 2011. This provides a global perspective on how different countries contribute to CO2 emissions.

3. Global CO2 Emissions in 2011

Visualization: A histogram of CO2 emissions per capita for different countries in 2011.

![](https://github.com/sujikathir/Co2-Emission-Vs-GDP/blob/main/images/4.%20per%20capita.png)

Observation: The USA, with ~18 metric tons per capita, stands out as having significantly higher emissions compared to many other countries.

## Relationship between GPD and CO2 Emissions in USA

1. Visualizing GDP Per Capita Over Time
   
Visualization: I plotted GDP per capita over time to observe economic trends:

![](https://github.com/sujikathir/Co2-Emission-Vs-GDP/blob/main/images/5.%20gdp.png)

Trend Analysis: CO2 emissions per capita in the USA have declined over the analyzed period, while GDP per capita has generally increased.

2. Comparing GDP and CO2 Emissions

To compare GDP per capita with CO2 emissions per capita, I ensured the data covered the same time frame.

Visualization: I created a scatter plot to visualize their relationship

![](https://github.com/sujikathir/Co2-Emission-Vs-GDP/blob/main/images/6.%20scatterplot.png)

Relationship Between GDP and CO2 Emissions: The scatter plot and correlation analysis show a weak relationship (correlation coefficient: 0.077), suggesting that economic growth does not directly translate to higher or lower CO2 emissions.

## Conclusion

This analysis provides insights into the relationship between economic growth and environmental impact in the USA. The findings highlight the complexity of balancing economic development with environmental sustainability, emphasizing the need for policies that promote green growth.

