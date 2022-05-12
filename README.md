# 2020nyc_subway_ridership
# NYC MTA Safety Barrier Installation Project
- author(s): Xing Huang, Xiaoguang Zeng, Xiaohan Yu, Lucy Li
- date created: 05/11/22


Project Objective: Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications

Project Tools:
The tools used to build this Data Warehouse were: (change this to make it applicable to your project)
1. For data integration - python
2. For data warehousing - Google BigQuery
3. For Business Intelligence - Tableau

## Kimball Lifecycle Project Stages

### Project Planning

Motivation for the project:
According to ABC News, over 37 people died from January 2021 to July 2021 after being hit by NYC trains. 30 people were shoved onto tracks and countless were injured (Deliso, 2022). Calls have grown among New Yorkers after another victim was fatally shoved onto the subway tracks in front of an oncoming train in January 2022. It is in demand for the MTA to revisit the idea of installing protective barriers in New York train stations. Considering MTA’s limited budget, we will run a series of analyses to find which 10 New York City subway stations need subway platform doors the most. 

We will use MTA 2020’s Turnstile Data to find the top 10 New York City subway stations with the most ridership to install subway platform doors. We will also take a look at NYC 2020’s For-Hire Vehicle Trip Record Data to observe if there is any overall association or trend between subway ridership and for-hire vehicle ridership. We wish to direct part of them back to MTA’s service by installing platform doors, with the assumption that better subway infrastructure can increase subway ridership. Our goal is to make New York residents feel safer about taking the subways, promoting subway ridership, as well as bringing down subway crime.


Description of the issues or opportunities the project will address:
Installing safety subway platform barriers would prevent riders from being pushed onto tracks. Other than the purpose of protecting more lives, it will help New York City’s economy by increasing MTA’s revenue. Because installing safety barriers will lower the fear of NYC residents taking subways, more people will return to MTA from for-hire vehicle companies.

Project Business or Organization Value:
The project can promote New York subway ridership and bring down subway crime which will bring a beneficial impact on New York City’s economy. We estimate this project will increase MTA’s revenue by 5% in the first year after installing platform doors in 10 major subway stations. 
This project will also protect more New York residents from subway crime, making them feel safer about living in New York, and preventing people from escaping New York City.

Data Sources:
1. NYC MTA 2020 Subway Traffic Volume
2. NYC 2020 High Volume FHV Trip Records

### Business Requirements Definition

List of Data Warehouse KPIs:
1. Subway Average Daily Traffic Volume per Station
2. Subway Year Total passengers per Borough
3. Total Traffic Volume per Month
4. For-hire vehicle daily average ridership by Neighborhood
5. For-hire vehicle ridership per month

### Dimensional Model

This project's Dimensional Model consists of (2) Facts and (5) Dimensions

![dimensional_model](https://user-images.githubusercontent.com/52082519/167986125-4f011619-805e-4d98-bc15-ca2d32bc8676.png)

This project's Kimball Bus Matrix:

![kimball_bus](https://user-images.githubusercontent.com/52082519/167986279-736f2332-74d5-4529-ba04-f18a36a1fa43.png)

### Business Intelligence Design and Development

List of Visualizations for each KPI:
1. Ranked horizontal bar chart for the comparison of train station's daily average traffic volume to the traffic volume of each station
2. Bar Chart to compare the annual total subway ridership between boroughs
3. Line charts to show the overall change in the number of ridership throughout 2020
4. Ranked horizontal bar chart to compare the daily average of for-hire vehicle ridership in each neighborhood
5. Area chart for the comparison of for-hire vehicle ridership per month

BI Application Wireframe design:
![wireframe](https://user-images.githubusercontent.com/52082519/167986331-863be162-49fc-4ae0-aed3-b1d6f79f2de3.png)


Picture of final Dashboard:

![dashboard1](https://user-images.githubusercontent.com/52082519/167986383-81200e8f-ddd8-4125-96f5-47e954d0de0d.png)

![dashboard2](https://user-images.githubusercontent.com/52082519/167986467-61e1633a-f086-4e85-aaec-f4a99218209a.png)

### Deployment

The project was deployed on Tableau Public: (link here)
1.https://public.tableau.com/app/profile/xiaohan.yu/viz/dashboard_16517199179900/subway2020?publish=yes 
2. https://public.tableau.com/app/profile/xiaohan.yu/viz/dashboard_16517199179900/fhv2020 
