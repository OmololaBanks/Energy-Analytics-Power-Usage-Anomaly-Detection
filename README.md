# Energy-Analytics-Power-Usage-Anomaly-Detection

## Project Overview
This project delivers an interactive analytics dashboard for detecting abnormal household energy consumption and preventing energy waste using smart meter data. The solution focuses on identifying energy spikes, understanding their underlying causes, and enabling proactive, data-driven interventions at both customer and regional levels.
Designed around real-world energy utility challenges, the dashboard demonstrates end-to-end data analysis, KPI design, anomaly detection logic, and executive-focused visual storytelling. It supports operational decision-making by highlighting high-risk customers, regions, housing types, and time periods associated with abnormal energy usage.

## Project Objectives
•	Detect abnormal energy usage spikes at the household level
•	Compare actual energy usage against expected baseline consumption
•	Identify key drivers of energy spikes (behavioral vs appliance-related)
•	Analyze spike patterns by region, housing type, weekday/weekend, and time
•	Enable customer-level and region-level filtering for targeted insights
•	Support proactive energy efficiency and customer engagement strategies

## Data Sources
•	Smart Meter Data:
o	Reading timestamp
o	Energy usage (kWh)
o	Customer ID and customer name
o	Region
o	Housing type
•	Derived Attributes:
o	Spike indicators
o	Baseline usage
o	Spike intensity and percentage
o	Weekday vs weekend classification

## Data Preparation
•	Cleaned and structured raw smart meter readings for analysis
•	Corrected timestamp interpretation issues caused by DD/MM vs MM/DD locale differences
•	Standardized date-time fields for accurate daily and hourly analysis
•	Engineered features including:
o	Time-based attributes (day, weekday/weekend)
o	Energy baselines for normal usage comparison
o	Spike counters and spike intensity metrics
o	Housing type and regional segmentation
•	Validated data consistency across all dashboard views

## Key KPIs
•	Total Energy Usage (kWh)
•	Number of Customers
•	Total Regions
•	Spike Count
•	Alert Count
•	Resolved Count
•	Average Spike Detected (%)
•	Spike Threshold (%)
•	Daily Average Energy Usage by Housing Type

## Key Insights
•	Energy usage remains broadly stable but shows late-period increases driven by seasonal and behavioral changes
•	A small number of regions contribute a disproportionate share of total energy consumption
•	Actual energy usage closely tracks baseline levels, with spikes driven by short-term events rather than structural inefficiency
•	Energy spikes are caused by a mix of behavioral factors and appliance-related issues
•	High-usage customers are significantly more prone to abnormal energy spikes
•	Weekday energy spikes exceed weekend spikes, particularly in urban regions
•	Detached homes show the highest spike intensity, while semi-detached homes remain the most energy-stable
•	Regional trends are often driven by a small subset of high-impact customers rather than widespread inefficiency

## Dashboard Features
•	Interactive KPI tiles for high-level energy monitoring
•	Time-series analysis of energy usage and spike intensity
•	Region- and housing-type-based spike distribution analysis
•	Weekday vs weekend spike comparison
•	Customer and region filters that dynamically update all visuals
•	Cause-of-spike breakdown for targeted interpretation
•	Executive-friendly layout optimised for decision-making and storytelling

## Business Value
•	Enables early detection of abnormal energy usage before billing cycles
•	Supports targeted energy efficiency interventions instead of blanket policies
•	Reduces customer complaints related to unexplained energy bills
•	Helps utilities prioritize high-risk customers and regions
•	Aligns operational efficiency with sustainability and energy waste reduction goals

## Tools Used
•	Google Sheets – data cleaning, preprocessing, and feature engineering
•	Tableau Public – interactive dashboards and visual analytics
