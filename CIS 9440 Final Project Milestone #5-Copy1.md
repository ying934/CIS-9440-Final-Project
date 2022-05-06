# Project Name here
- Author(s): Ying Chen, Jiawen Chen,Gexing Ding, Wanmei He
- Date Created: 5/6/2022
- Class: CIS 9440

Project Objective: Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications

Project Tools:
The tools used to build this Data Warehouse were: (change this to make applicable to your project)
1. For data integration - python
2. For data warehousing - Google BigQuery
3. For Business Intelligence - Tableau

## Kimball Lifecycle Project Stages

### Project Planning

Motivation for project:

More and more incidents in recent years where riders were shoved onto the tracks. For passengers’ safety, there is a need to add platform screen doors or protective facilities at subway station.

Description of the issues or opportunities the project will address:

Metropolitan Transportation Authority (MTA) provides convenient transportation in New York City, but how many subway accidents have occurred in 2021, 2020, or 2019 ? How many injuries case are there ? Is the number of accidents increasing or decreasing ? Which stations will need to install the platform screen door the most ?
To answer these questions, our data warehouse will combine the number of subway stations, daily ridership data, subway stations events data to analyze the situation of each station.

Project Business or Organization Value:

Since more and more incidents and injuries in the subway during recent years, people are more preferred on Uber or other alternatives. If there is a clear analysis of the safety level of each subway station. MTA department can provide a budget plan to install platform screen door or optimize protective facilities at different stations. They can also offer the transparency plan for all riders, which can increase rider’s trust
and thus increase its daily ridership. Also, this plan may be increase revenue by reducing compensation for injuries and other maintenance costs.

Data Sources:

1. MTA NYC Incidents https://data.ny.gov/Transportation/511-NY-MTA-Events-Beginning-2010/i8wu-pqzv
2. Subway Station Data https://data.cityofnewyork.us/Transportation/Subway-Stations/arq3-7z49
3. Subway Ridership Data https://new.mta.info/agency/new-york-city-transit/subway-bus-ridership-2020

### Business Requirements Definition

List of Data Warehouse KPI's:
1.Average annual ridership per station
2.Average daily ridership per station based on weekdays and weekends.
3.Total number of subway stations by borough
4.Total accidents/injuries case by category by borough in 2020
5.The number of subway lines per station


### Dimensional Model

This project's Dimensional Model consists of (x) Facts and (y) Dimensions

Use correct file path here to show picture of dimensional model...
![Dimensional%20Model.png](attachment:Dimensional%20Model.png)

This project's Kimball Bus Matrix:

![Kimball%20BUS%20Matrix.PNG](attachment:Kimball%20BUS%20Matrix.PNG)



### Business Intelligence Design and Development

List of Visualizations for each KPI:
1. Bar Chart for Average annual ridership per station
![KPI%20#1-%20Annual%20Ridership%20Top25.png](attachment:KPI%20#1-%20Annual%20Ridership%20Top25.png)

2. Bar Chart - Compariosn of Average daily ridership per station based on weekdays vs Weekends
![KPI%20#2%20-%20Average%20Weekdays%20Top%2025.png](attachment:KPI%20#2%20-%20Average%20Weekdays%20Top%2025.png)
![KPI%20#2%20-%20Average%20Weekdays%20Top%2025.png](attachment:KPI%20#2%20-%20Average%20Weekdays%20Top%2025.png)

3. Packed bubble chart for Total number of subway stations by borough
![KPI#%203%20-%20Subway%20Station%20by%20Borough.png](attachment:KPI#%203%20-%20Subway%20Station%20by%20Borough.png)

4. Packed bubble chart for Total accidents/injuries case by category by borough in 2020
![KPI#4%20-%20Incidents%20cases%20by%20Borough%20in%202020.png](attachment:KPI#4%20-%20Incidents%20cases%20by%20Borough%20in%202020.png)

5. Bar Chart for The number of subway lines per station
![KPI#5%20-%20Subway%20Line%20per%20Station.png](attachment:KPI#5%20-%20Subway%20Line%20per%20Station.png)

BI Application Wireframe design:
![image.png](attachment:image.png)


Picture of final Dashboard:

## Use correct file path here to show picture of Dashboard:

Dashboard #1 
![Dashboard%20#1.PNG](attachment:Dashboard%20#1.PNG)

Dashboard #2
![Dashboard%20#2.png](attachment:Dashboard%20#2.png)

### Deployment

The project was deployed on Tableau Public: (link here)

Dashboard 1: https://public.tableau.com/app/profile/wanmei.he/viz/Milestone4Dashboard1/Dashboard1?publish=yes

Dashboard 2: https://public.tableau.com/app/profile/wanmei.he/viz/Milestone4Dashboard2/Dashboard2?publish=yes


```python

```
