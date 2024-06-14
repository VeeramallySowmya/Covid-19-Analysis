# Analysis of COVID-19 Impact on Public Health 

## Introduction:

The COVID-19 pandemic has had a profound impact on public health worldwide. The ability to acquire and investigate data is crucial to understanding these effects. Data visualization translates information into visual contexts, such as maps or graphs, making it easier for the human brain to comprehend and derive insights. This project analyses the COVID-19 pandemic's impact using Power BI to identify trends, create hypotheses, and build a better understanding of the situation.
<br>
The pandemic has led to unprecedented changes in various sectors. This project aims to analyze data related to COVID-19 cases, deaths, and other relevant indicators to understand the pandemic's multifaceted impact. By comparing different datasets, we can identify potential reasons behind observed trends and propose measures to mitigate adverse effects.
<br>
In today's world, accurate data visualization is essential for making informed decisions. The project utilizes data from [https://www.worldometers.info/coronavirus/](https://www.worldometers.info/coronavirus/) . Despite challenges in obtaining consistent and comprehensive data, this analysis aims to provide meaningful insights into the COVID-19 pandemic's impact.
<br>

## Methodology:
<br>
The data for this project was web-scraped using Python from reputable public health website( https://www.worldometers.info/coronavirus/ )and aggregated to create a comprehensive dataset. Web scraping allowed us to collect up-to-date information on COVID-19 cases, deaths, recoveries, and testing metrics from various countries. This method was crucial in obtaining real-time data necessary for accurate analysis and visualization.

## Variables:
Key variables include:
- Country/Region
- Total Cases
- New Cases
- Total Deaths
- New Deaths
- Total Recovered
- New Recovered
- Active Cases
- Serious/Critical Cases
- Total Cases per 1M population
- Deaths per 1M population
- Total Tests
- Tests per 1M population
- Population
- New Cases per 1M population
- New Deaths per 1M population
- Active Cases per 1M population

These variables were selected to provide a comprehensive overview of both health impacts. The data spans from the pandemic's onset to the most recent available updates.

## Python Web Scraping:
The web scraping was performed using Python libraries such as BeautifulSoup and Requests.
The script scrapes the data from the specified URL, processes it into a structured format, and saves it as an excel file for further analysis.

## DAX Queries:
To analyze and visualize the data in Power BI, several DAX (Data Analysis Expressions) queries were used to create calculated columns and measures for insightful analysis. Some key DAX queries used include:
•	Total Cases:
•	Total Deaths:
•	Total Recovered Casses:
•	Recovery Rate:
•	Mortality Rate
These DAX queries helped in creating detailed and dynamic visualizations that provide a comprehensive view of the COVID-19 impact across different countries.

## Bookmark Technique:
The bookmark technique in Power BI was used to create interactive navigation between different pages and visualizations within the report. This technique enhances the user experience by allowing seamless transitions and focused analysis on specific aspects of the data. Bookmarks were created for each key visualization and dashboard to enable quick access and comparison.

## Analysis:

### Visualization 1: Total COVID-19 Cases and Deaths by Country
 ![image](https://github.com/VeeramallySowmya/Covid-19-Analysis/assets/31852272/f62754c5-f263-456f-a22c-df10b736389e)


This visualization shows the total COVID-19 cases and deaths globally by country. It highlights the countries with the highest impact in terms of both cases and deaths, providing a clear picture of the global distribution of the pandemic.

### Visualization 2: Active COVID-19 Cases by Country
 ![image](https://github.com/VeeramallySowmya/Covid-19-Analysis/assets/31852272/b7b66fb3-66c7-40bf-9319-cb2d90def9d0)


This chart shows the number of active COVID-19 cases by country. It reveals the current burden on healthcare systems and the regions that are still struggling with ongoing outbreaks.

### Visualization 3: Serious/Critical COVID-19 Cases by Country
 ![image](https://github.com/VeeramallySowmya/Covid-19-Analysis/assets/31852272/e0334e7e-d28f-4fc5-bd93-28585d0ec45f)

This visualization illustrates the number of serious/critical COVID-19 cases by country. It highlights the severity of the pandemic in different regions and helps identify countries that may require additional healthcare resources.


### Visualization 4: Total Tests Conducted by Country
 ![image](https://github.com/VeeramallySowmya/Covid-19-Analysis/assets/31852272/2ce22071-b23f-4a01-a8ea-ee458d5a3568)

This chart shows the total number of COVID-19 tests conducted by country. It provides insight into the testing capacity and coverage of different regions, which is crucial for understanding the true extent of the pandemic.

### Dashboard 1: Global Overview of COVID-19 Impact
![image](https://github.com/VeeramallySowmya/Covid-19-Analysis/assets/31852272/55d72ca9-4bae-4ecb-bd07-390b6bcb3c9f)

 
This interactive dashboard provides a global overview of the COVID-19 impact, combining key metrics like total cases, deaths, active cases, and tests conducted. Users can filter by region and button to get detailed insights. This dashboard is a valuable tool for policymakers and public health officials.


### Dashboard 2: Trend Analysis of New Cases, Deaths, Recovered and active cases
![image](https://github.com/VeeramallySowmya/Covid-19-Analysis/assets/31852272/4e67571b-672b-45cb-8464-c85f52018035)

 
This dashboard focuses on the new cases and deaths reported, featuring visualizations that track the daily changes and trends. It helps identify which countries are currently experiencing surges and the effectiveness of measures taken to control the spread.

### Dashboard 3: Detailed information of Cases, Deaths, Recovered and Tests Conducted
![image](https://github.com/VeeramallySowmya/Covid-19-Analysis/assets/31852272/cb3cf86a-d40e-4bb8-9c6d-482cb5738b44)


  
## Conclusion:
<br>
The COVID-19 pandemic has profoundly impacted public health globally. Through data visualization in Power BI, we can understand these effects more clearly. This project highlights the importance of comprehensive data collection and analysis in managing the pandemic.

## Key findings include:
- Countries with higher testing rates tend to have better control over the spread of the virus.
- Active cases and serious/critical cases are crucial indicators of the current burden on healthcare systems.
- Ongoing monitoring of new cases and deaths is essential for identifying and responding to hotspots.

By providing detailed visualizations and analyses, this project aims to support informed decision-making to mitigate the pandemic's adverse effects and promote recovery. The use of Python for web scraping to collect data has been instrumental in ensuring the analysis is based on the most current information available.
