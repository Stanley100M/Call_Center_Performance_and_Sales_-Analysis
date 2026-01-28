# Power Pivot Metrics & Calculations

This document describes the **metrics and calculations** created using **Power Pivot and Pivot Table implicit** measures to support the analysis and Excel dashboard.

All metrics were created using:

* Power Pivot data model

* Pivot Table value field settings (Sum, Count, Average)

* Grouping and filtering logic

## Core Metrics

**1.Total Calls**

   **Definition**: Total number of calls handled.

   **Method**:

* Value field: Call Number

* Aggregation: Count

**Business Use**:

* Measures call volume

* Used across all call distribution charts

**2.Total Sales**

**Definition**: Total revenue generated from calls.

**Method**:

Value field: Purchase Amount

Aggregation: Sum

**Business Use**:

* Tracks overall sales performance

* Used in monthly sales trend and sales by representative

**3.Total Call Duration**


**Definition**: Total time spent on calls.

**Method**:

* Value field: Duration (seconds)

* Aggregation: Sum

**Business Use**:

* Measures agent workload

* Used in call duration and representative analysis

**4.Average Satisfaction Rating**

**Definition**: Average customer satisfaction score.

**Method**:

* Value field: Satisfaction Rating

* Aggregation: Average

**Business Use**:

* Evaluates service quality

* Used in satisfaction distribution charts

**5.Total Happy Calls**

**Definition**: Number of calls with high satisfaction ratings.

**Method**:

**Report filter**: Satisfaction Rating ≥ 4

* Value field: Call Number

* Aggregation: Count

**Business Use**:

* Measures customer experience quality

* Used as a KPI in the dashboard

## Agent Performance Metrics
**6. Calls per Representative**

**Method**:

* Rows: Representative

* Values: Count of Call Number

**Insight Provided**:

* Identifies high-volume agents

* Helps balance workload

**7.Sales per Representative**

**Method**:

* Rows: Representative

* Values: Sum of Purchase Amount

**Insight Provided**:

* Highlights top revenue contributors

## Call Duration Analysis
**8.Calls by Duration Bucket**

**Method**:

* Rows: Duration Bucket

* Values: Count of Call Number

**Insight Provided:**

* Shows how long calls typically last

* Useful for efficiency analysis

**9.Monthly Sales Trend**

**Method:**

* Columns: Month (from Date of Call)

* Values: Sum of Purchase Amount

**Insight Provided:**

* Reveals seasonality and trends
































































