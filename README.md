
# Real Estate Market Analytic End to End Project
This project is about to capitalize real estate data for 
assisting investor to obtain optimal investment decision 

# Introduction & Goals
The end of product of this project is the complete real estate analytic tool, from data ingestion until data visualization.
The project demonstrates the process from data collection, data cleaning, data transformation, and data visualization. The project is developed using Azure data engineering platform, and utilize Power BI as tool to develop data visualization.

# Contents
- [The Architecture Diagram](#the-architecture-diagram)
- [The Data Set](#the-data-set)
- [Used Tools](#used-tools)
- [Pipelines](#pipelines)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)
- [Follow Me On](#follow-me-on)


# The Architecture Diagram

![Screenshot 2025-03-11 114437](https://github.com/user-attachments/assets/41332464-9fc7-44d2-9507-9c131bc55f69)

# The Data Set
The data sources taken from Zillow, AirDNA, Rental, Crime Data API. Zillow and AirDNA have been the popular platforms used to analyze real estate market both for long term and short term rental market.  

# Used Tools
- Synapse Data Analytics is used to orchestrate the entire pipeline, and also write python script to collect the data
- Databrick is used in data extraction and transformation process
- Datalake Gen2 is used to store raw data and transformed data

# Pipelines
The pipeline design is divided into 3 phases :
- Phase 1 : Collecting and transforming property on market data as a base for next data collection and transformation
- Phase 2 : Collecting crime, rental, AirBNB data based on targeted market area
- Phase 3 : Transforming crime, rental, AirBNB data into ready use format

# Visualization
Power BI is used as data visualization tool, due to the easy connectivity with azure platform. 
![Screenshot 2025-03-01 094921](https://github.com/user-attachments/assets/7c18e0b2-5392-4fa1-83d0-7a9e97e9aa0d)

# Batch Processing
The batch processing is scheduled every week to obtain significant amount of data change based on targeted market analysis

# Transformed Data Model
![Screenshot 2025-03-01 115329](https://github.com/user-attachments/assets/816cb36f-9996-4b78-93a2-bf8e2e66f76c)

# Demo
- You could add a demo video here
- Or link to your presentation video of the project

# Conclusion
The project turns to be very useful for individual investor with the key information presented in the dashboard and regular update.
The biggest challenge would be finding the relevant data that complement such analysis of an area such as crime data, demography, etc.
The other challenge would be the limitation of each of data source API how many request that can be made during certain amount of time, finding the optimal request would be the trade off between how much we will get then also how fast the data collection can be done. 

# Follow Me On
[My LinkedIn Profile](https://www.linkedin.com/in/bagus-adiyanto-29a9a229/)

