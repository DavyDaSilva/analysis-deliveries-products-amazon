# Amazon Delivery Delay Analysis

## 1. Business Problem  
The company is facing an increase in the number of deliveries completed outside the expected timeframe, which has generated customer dissatisfaction, an increase in complaints, and a risk of loss of trust in the brand.  

The main business challenge is to understand why delays occur, identify where they are concentrated, and generate clear information that supports operational decisions to reduce the delay rate and improve delivery predictability.  

## 2. Context
The delivery operation involves different variables that directly impact delivery time, such as:  

● weather conditions,  
● traffic,  
● type of vehicle used,  
● delivery area,  
● courier profile,  
● product category.  

The company already has operational data recorded in a historical database, but does not use this information analytically to support strategic decisions.

The objective of this project is to transform raw delivery data into actionable insights, using descriptive analyses and simple visualizations that can be understood by areas such as Operations, Logistics, and Management.

## 3. Analysis Assumptions
To carry out the analysis, the following assumptions were adopted:  

● the delivery status (Delivery_Status) is considered the official source to identify delayed deliveries (delay) and on-time deliveries (ontime).  
● the delivery time (Delivery_Time) is represented in minutes.  
● records with missing values in columns such as traffic or weather were treated as “unknown information” or excluded when necessary.  
● the analyses were performed with a focus on pattern identification, not statistical causality.  
● the analyzed period represents a valid sample of the company’s recent operational behavior.  

## 4. Solution Strategy
The adopted strategy followed a structured data analysis approach:

1. Business problem understanding  
   Clearly identifying what constitutes a delay and why it is harmful to the company.  

2. Data exploration and organization  
   Understanding columns, data types, and possible inconsistencies.  

3. Descriptive analysis  
   Calculation of metrics such as number of deliveries, delay rate, and delivery time statistics.  

4. Delay segmentation  
   Evaluation of delays across different dimensions:

○ time,  
○ area,  
○ weather,  
○ traffic,  
○ vehicle,  
○ product category.  

6. Data visualization  
   Creation of clear charts to facilitate interpretation of results and communication with the business.

## 5. Analysis Insights
The data analysis allowed the identification of relevant patterns, such as:  

● the average delivery time is 125 min (2h) with a standard deviation of 52 min (2h). The fastest delivery took 10 min and the slowest took 270 min (4.5h).  
● the “Semi-Urban” area is the only area with more delayed deliveries than on-time deliveries.  

<p align="center">
  <img src="img/g02.png" width="45%" />
  <img src="img/g03.png" width="45%" />
</p>  

● delays increase on cloudy and foggy days and decrease on sunny days.  
● motorcycles present a higher delivery delay rate compared to other vehicle types.  

<p align="center">
  <img src="img/g04.png" width="45%" />
  <img src="img/g05.png" width="45%" />
</p>

● heavy traffic (Jam) presents more delays.  
● the longest delays occurred in deliveries to the “Semi-Urban” area performed by motorcycles.  
● couriers over 30 years old tend to delay deliveries more than couriers under 30 years old.  
● deliveries are evenly distributed across categories, except for the “Others” category, which represents 43% of deliveries.  
● the lowest ratings occur in deliveries to the “Semi-Urban” area using motorcycles, which also present the highest volume of delays.  

These insights show that delays are not random, but rather the result of operational factors such as delivery area and vehicle type.

## 6. Results
As a result of the project, the following initiatives are proposed:  

● deepen the understanding of why the “Semi-Urban” area has the highest delay volumes.  
● change the delivery vehicle type used in the “Semi-Urban” area.  
● visual diagnosis of the most critical operational points.  
● analytical foundation to prioritize corrective actions.  
● reports and charts that can be used by non-technical areas.  

- Link to the full report: https://lookerstudio.google.com/reporting/0337fdeb-651b-46f1-9256-54412af57bd1

Additionally, the project demonstrates how data analysis can transform operational data into practical decisions, even when using simple techniques.

## 7. Next Steps
Based on the obtained results, the recommended next steps are:  

● create specific action plans for the most critical areas, vehicles, and conditions.  
● continuously monitor delay rates through dashboards.  
● evaluate training initiatives or operational adjustments for couriers and routes.  
● integrate predictive analytics to anticipate delay risks.  
● deepen the analysis with additional data, such as traveled distance or peak hours.  

This project serves as a first step toward a data-driven culture, where operational decisions are guided by evidence rather than perception.

Portfolio Project Submission Form  
https://forms.gle/dZ54sxez4rZ52QQ98


