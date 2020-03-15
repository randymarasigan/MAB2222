# MABA 2222 Coronavirus Hackathon Challenge

This site contains resources for the MABA 2222 SY 2020 Hackathon Challenge. 


# Title: A Community Portal for tracking COVID-19 cases worldwide.
 
## Abstract

The World Health Organization and the Government of affected countries need close monitoring of virus cases per country to implement countermeasures to combat the increase of coronavirus infection.

We are creating a portal that links to dashboards and web maps. These resources are powered with various datasets worldwide, With the help of the ArcGIS online tool to visualize and create an interactive live map, maps and dashboards can be viewed and drilled down by users globally. A dashboard that can provide near real-time visibility of the rate of increase or decrease of infections per country will enable authorities a proactive effort to control the spread. 

The system should alert the public users for new cases in the country, increasing cases, and even declining cases of infection.


## Objective

* The coronavirus outbreak has global attention due to its unpredictable nature and high infection rate. 
* The goal is to conceptualize a business analytics project tackling the Coronavirus
* Scenario: A solution to help decision makers address the Coronavirus

## Specific Project Objective

Build a tracking tool for the stakeholders to have an understanding of the situation using the available data sources.

The project aims to answer the following questions:
How to quickly see the areas around the world that have increasing cases of coronavirus infections?
Which country needs immediate attention because of the constant and significant increase in cases of infections?
What is the status of COVID-19 infections in the country?
What is the current rate of infections in a specific location of interest?
What is the COVID-19 death rate in the country?
How effective are the government mitigation efforts to stop the infections and deaths? 

## Datasets and Resources

### Data and Analysis

#### Dataset used is from the following sources:

Data sources:
1. Data from the World Health Organization
2. John Hopkins University Data and Feature Layers
3. Dashboard inspiration: https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6
4. Feature Layers: https://www.arcgis.com/home/item.html?id=c0b356e20b30490c8b8b4c7bb9554e7c
5. COVID-19 Data (Github): https://github.com/CSSEGISandData/COVID-19
6. DOH NCOV data
7. Dashboard inspiration: https://ncovtracker.doh.gov.ph/
8. Local cases: https://docs.google.com/spreadsheets/d/1wdxIwD0b58znX4UrH6JJh_0IhnZP0YWn23Uqs7lHB6Q/edit#gid=0
9. Philippine data on COVID-19
Reference: https://docs.google.com/spreadsheets/u/1/d/1wdxIwD0b58znX4UrH6JJh_0IhnZP0YWn23Uqs7lHB6Q/edit#gid=0

Data Processing Tools:
1. ArcGIS Pro Desktop - Used ArcGIS Pro Desktop for data processing and GIS Mapping
2. ArcGIS Online - Used ArcGIS Online for the Dashboard.
3. MS Excel / Google Sheets

Visualization/Portal tools:
1. ArcGIS Online - Used for the main portal (COVID-19 Cases Portal) - https://gisdatascience.maps.arcgis.com/home/index.html 
2. ArcGIS Online (Operations Dashboard) - Our Dashboard is built using the ArcGIS Online Dashboard -  https://arcg.is/0jvCW8
3. Google Data Studio for the Descriptive Analytics Dashboard - https://datastudio.google.com/u/0/reporting/1sfMyDu0OSGRbZUmEMbSpJg8KIz8bH6U6/page/EtLIB

Mapping visualization: All web maps, app, and dashboard can be accessed through the portal -https://gisdatascience.maps.arcgis.com/home/index.html
1. Online mapping with various themes (thematic layers)
- Confirmed cases - Shows the Confirmed cases
- Deaths - Shows the no. of deaths
- Recovered - Shows the no. of recovered patients
- Countries affected - Countries affected with counts (Confirmed, Deaths, Recovered)
- Location map - Indicated the center point of cases in a county - Web Application was build for this - https://gisdatascience.maps.arcgis.com/apps/webappviewer/index.html?id=fe84cc1694aa4bea88de0cf57cd24fbb

Charts: All charts can be viewed in the Operations Dashboard and Google Data Studio Dashboard (https://arcg.is/0jvCW8, https://datastudio.google.com/u/0/reporting/1sfMyDu0OSGRbZUmEMbSpJg8KIz8bH6U6/page/EtLIB)
1. Cumulative cases per country
2. Scorecards/summary (confirmed cases, death, recovered)
3. For local cases, a separate dashboard is created
4. Gender
5. Nationality
6. Age

Problems to be solved through algorithms:
Rate of increase of the virus spread (Global/Country level) - This will be future work as data becomes more readily available.

### Actions

Through the real-time visibility of infection cases around the world, authorities will be alerted and able to implement proactive and effective measures to prevent the virus from further spreading.

The dashboard will also aid the government to apply certain actions and necessary interventions when it comes to travel advisory or travel bans.

Our local communities will also be aware of the current situation in the country by providing them summarized information through dashboards.

### Results

Effectiveness of the COVID-19 Community Portal will be measured by:

1. The decline in the cases of infections around the world which can be seen in the dashboards.
2. Increase in the number of recoveries of those infected.
3. The decline in the number of new cases in the Philippines as confirmed by the data processed and visualized in the dashboard.
4.Able to help the health authorities with the demographic information of infected patients that can assist in the clinical correlations.
5. COVID-19 Cases in the Philippines (Age, Nationality, Case Trend or rate of increase, Patient Status).

### Important Links for the Project:
GitHub Link for this project: Repository: https://github.com/randymarasigan/MAB2222

COVID-19 Cases Portal: https://gisdatascience.maps.arcgis.com/home/index.html

Worldwide COVID-19 Cases Dashboard: https://gisdatascience.maps.arcgis.com/apps/opsdashboard/index.html#/ad9abb1c78ab4736ae55a8f83754f170

Worldwide COVID-19 Cases Web Application: https://gisdatascience.maps.arcgis.com/apps/webappviewer/index.html?id=fe84cc1694aa4bea88de0cf57cd24fbb

Philippines COVID-19 Cases Dashboard: https://datastudio.google.com/u/0/reporting/1sfMyDu0OSGRbZUmEMbSpJg8KIz8bH6U6/page/HAYIB

Web Scene (3D Visualization): https://gisdatascience.maps.arcgis.com/home/webscene/viewer.html?webscene=dcb7173c87044339b031fd6c3f3cff7b


## License

This work is part of an academic requirement for Masters in Advanced Business Analytics (MABA) 2222 Business Domain. This work is provided as-is under the terms of Creative Commons Attribution 4.0 International ([CC-BY-4.0](https://choosealicense.com/licenses/cc-by-4.0/#)) license. 

**Note: Data and analysis featured in this repository are products of voluntary contributions and do not consitute official health advisory. Please contact your health ministry for latest updates on Coronavirus.**
