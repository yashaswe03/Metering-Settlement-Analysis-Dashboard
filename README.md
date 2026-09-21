# Metering & Settlement Power BI Dashboard

## Project Overview

The Metering & Settlement Power BI Dashboard is an interactive business
intelligence solution developed to monitor meter movements, electricity
consumption, and meter-related business performance over a rolling 12-month
period from August 2021 to July 2022.

The dashboard helps the Metering & Settlement team analyze:

- Meters gained
- Meters lost
- Net meter movement
- Active and lost meters
- Monthly meter movements
- Consumption trends
- Consumption by meter type
- Consumption by meter company
- Meter-level consumption
- Loss reasons
- Meter-level details

---

## Business Problem

The Metering & Settlement team needs a centralized dashboard to monitor
meter acquisition, meter losses, and electricity consumption.

The objective is to provide an interactive dashboard that allows users to
identify movement trends, analyze meter types, monitor consumption patterns,
and investigate individual meters.

---

## Business Requirements

The dashboard addresses the following requirements:

1. Display total meters gained during the selected period.
2. Display total meters lost during the selected period.
3. Show monthly gained and lost meters.
4. Allow analysis by Meter Type.
5. Display overall Net Gain/Loss.
6. Display total monthly consumption.
7. Provide filtering by Month/Date and Meter Type.
8. Provide analytical insights including:
   - Trends
   - Meter type analysis
   - Cumulative meter movement
   - Consumption patterns
   - Highest/lowest gain and loss months

---

## Tools & Technologies

- Power BI
- DAX
- Power Query
- Excel
- Data Modeling
- Data Visualization

---

## Dashboard Pages

### 1. Executive Overview

Provides a high-level summary of the business performance.

Key metrics include:

- Meters Gained
- Meters Lost
- Net Gain/Loss
- Total Consumption
- Average Consumption

It also provides:

- Monthly Meter Gains vs Losses
- Highest Gain Month
- Lowest Gain Month
- Highest Loss Month
- Lowest Loss Month
- Executive Insights
- Date and Meter Type filtering

---

### 2. Meter & Consumption Analysis

Provides analysis of:

- Total Meters
- Total Consumption
- Average Consumption
- Consumption by Meter Type
- Cumulative Net Meter Movement
- Monthly Consumption
- Meter Consumption Details

---

### 3. Meter Status & Loss Analysis

Provides analysis of:

- Total Meters
- Live Meters
- Lost Meters
- Active vs Lost Meters
- Meters Lost by Reason
- Lost Meters by Meter Type
- Monthly Meter Loss Trend
- Lost Meter Details

---

### 4. Consumption Performance Analysis

Provides:

- Total Consumption
- Monthly Consumption Trend
- Consumption by Meter Type
- Consumption by Meter Company
- Meter Consumption Performance
- Date/Meter Type filtering

---

### 5. Meter Analysis

This page works as a meter-level drill-through page.

It provides details for the selected meter including:

- Selected Meter
- Meter Company
- Meter Status
- Meter Type
- Meter Consumption History
- Monthly Consumption
- Meter Information
- Daily Consumption Details

---

## Key Results

For the Aug 2021 – Jul 2022 analysis period:

- 661 meters were gained.
- 126 meters were lost.
- Net meter movement was +535.
- 845 meters were active/live.
- 155 meters were classified as lost in the overall meter status analysis.
- Total consumption was approximately 427.79M kWh.
- 546 meters were Domestic.
- 454 meters were Industrial.
- October 2021 recorded the highest meter gain with 82 meters.
- May 2022 recorded the lowest meter gain with 40 meters.
- March 2022 recorded the highest meter loss with 26 meters.
- February 2022 recorded the lowest meter loss with 6 meters.

---

## Key Insights

### Meter Movement

The dashboard shows positive net meter movement during the analysis
period, with meter gains exceeding meter losses.

### Monthly Trends

Monthly gain and loss trends help identify periods with higher meter
acquisition or loss activity.

### Meter Type

The dashboard allows comparison between Domestic and Industrial meters
for both meter movement and consumption.

### Consumption

Industrial meters account for the larger share of total consumption,
while monthly consumption trends allow changes in consumption to be
monitored over time.

### Loss Analysis

Loss reasons and monthly loss trends help the business investigate
meter attrition and identify periods requiring further investigation.

---

## Interactive Features

The dashboard includes:

- Date filtering
- Meter Type filtering
- Meter Company filtering
- Supply Status filtering
- Loss Reason filtering
- Interactive Power BI visual interactions
- Drill-through to individual meter analysis

---

## Data Model

The dashboard uses meter reference and consumption information to connect
meter-level information with daily consumption readings.

Main analytical entities include:

- Meters
- Meter Types
- Consumption
- Calendar
- DAX Measures

---

## DAX Measures

Examples of measures developed include:

- Total Meters
- Meters Gained
- Meters Lost
- Net Meter Gain/Loss
- Active Meters
- Total Consumption
- Average Consumption
- Monthly Meter Gain
- Monthly Meter Loss
- Loss Rate

---

## Business Value

The dashboard provides a centralized view of meter movement and consumption
performance.

It enables users to:

- Monitor meter growth and losses
- Identify monthly movement trends
- Compare meter types
- Monitor consumption
- Investigate meter losses
- Drill into individual meter performance
- Support operational planning and decision-making

---


