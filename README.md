# Call_Center_Performance_and_Sales_-Analysis(Excel | Power Pivot)
 ## Overview

This project analyzes call center performance, sales outcomes, and customer satisfaction using Excel and Power Pivot.

The goal is to uncover insights into:

* Call volume patterns

* Representative performance

* Sales trends

* Customer satisfaction levels

* Call duration behavior


The analysis culminates in an interactive Excel dashboard designed for operational and management decision-making.

## Business Questions Addressed

1. Which representatives handle the most calls and generate the highest sales?

2. How does call duration impact customer satisfaction and purchase amount?

3. What days of the week receive the highest call volumes?

4. Are shorter or longer calls associated with happier customers?

5. How does sales performance trend over the year?

6. How many number of calls have high satisfaction ratings?

## Dataset Description

The dataset contains call-level data with the following fields:

| Column Name                   | Description                                      |
|------------------------------|--------------------------------------------------|
| Call Number                  | Unique identifier for each call                  |
| Customer ID                  | Unique identifier for each customer              |
| Call Duration (Seconds)      | Total duration of the call in seconds            |
| Duration Bucket              | Categorized call duration range                  |
| Representative               | Call center agent handling the call (R01–R05)    |
| Date of Call                 | Date the call was placed                         |
| Purchase Amount              | Sales value generated from the call              |
| Satisfaction Rating          | Customer satisfaction score                     |
| Satisfaction Rating (Rounded)| Rounded customer satisfaction score              |
| Year                         | Year the call occurred                           |
| Day of Week                  | Day of the week the call occurred                |
| Gender                       | Customer gender                                  |
| City                         | Customer city                                    |

## Tools & Technologies Used

* Microsoft Excel

* Power Pivot (Data Model & DAX)

* Pivot Tables & Pivot Charts

* Excel Dashboards

## Key Metrics & Calculations

The following KPIs were created using Power Pivot measures:

* Total Calls

* Total Sales

* Total Call Duration per Representative

* Average Satisfaction Rating

* Total Happy Calls (High satisfaction ratings)

* Calls by Duration Bucket

* Calls by Day of Week

* Sales by Representative

* Sales Trend (January–December)

## Visualizations & Insights

1. **Call Volume Analysis**

    Bar Chart: Total number of calls per representative

    Bar Chart: Calls per day of the week (with representative filter)

    **Insight**: Identifies peak call days and workload distribution among agents.

2. **Sales Performance**

   Bar Chart: Total sales per representative

   Line/Column Chart: Monthly sales trend from January to December

   **Insight**: Highlights top-performing agents and seasonal sales patterns.

3. **Call Duration Behavior**

   Column Chart: Calls by duration bucket

   **Insight**: Majority of calls fall within 1 to 2 hours duration range, helping assess efficiency.

4. **Customer Satisfaction**

   Column Chart: Distribution of satisfaction ratings

   Measure: Average call rating

   Measure: Total happy calls

   **Insight**: Helps understand service quality and customer experience.

5. **Demographic Analysis**

   Column Chart: Male vs Female callers by city

   Cincinnati

   Cleveland

   Columbus

   **Insight**: Reveals caller demographics and city-level engagement.

## Interactive Excel Dashboard

An Excel dashboard was created to consolidate all KPIs and visuals into one interactive view.

Dashboard Features:

* Slicers for:

    * Representatives

* Real-time metric updates

* Visual comparison of sales, calls, and satisfaction

* Sales trend

## Key Insights Summary

* Certain representatives consistently outperform others in both call volume and sales

* Longer calls tend to show higher volume

* Sales show clear monthly trends with march being the peak month

* Most calls fall under 1-2 hours

* Customer satisfaction is generally positive, with room for improvement on longer calls



**Author**

[Stanley Eric]

Data Analyst

📊 Excel | Power Pivot | Data Visualization




















