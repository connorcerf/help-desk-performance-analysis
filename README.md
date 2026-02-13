# Improving Help Desk Resolution Speed and Customer Satisfaction

## Overview

This project analyzes help-desk ticket data to evaluate operational efficiency and its impact on customer satisfaction. The analysis identifies resolution bottlenecks, high-volume support areas, and gaps in customer feedback collection.

---

## Business Problem

Support teams must balance speed, quality, and resource allocation. Prolonged resolution times and unclear performance tracking can reduce customer satisfaction and limit scalability.

> **Primary Question:**  
> How can help-desk operations be optimized to reduce resolution time and improve customer satisfaction?

---

## Dataset

Each record represents a help-desk ticket and includes:
- Functional area (Filed Against)
- Priority and severity level
- Days open (resolution time)
- Customer satisfaction rating

The dataset combines operational performance metrics with customer experience data to provide a holistic view of help-desk performance.

## Tools Used

- Microsoft Excel (data cleaning & preparation)
- Microsoft Power BI (analysis & visualization)
- GitHub (documentation & version control)

---

## Data Preparation

The dataset was cleaned in Microsoft Excel by:

- Removing duplicate ticket records
- Standardizing categorical fields (priority, functional area)
- Handling missing satisfaction ratings
- Validating resolution time values

These steps ensured consistent and reliable reporting in Power BI.

---

## Operational Analysis

### 1. Ticket Volume by Functional Area

Systems and Access/Login account for the highest ticket volume, indicating potential system inefficiencies or user friction. These areas represent the largest drivers of help-desk workload and should be prioritized for process improvement.

![Tickets by Function](images/tickets_by_function.png)

---

### 2. Resolution Time by Priority

High-priority tickets are resolved faster on average. However, a small number of high-priority tickets remain open significantly longer than expected, indicating potential workflow bottlenecks.

Low-priority tickets remain open the longest, contributing to backlog accumulation.

![Days Open by Priority](images/max_days_open_by_priority.png)

![Days Open by Priority](images/days_open_by_priority.png)

---

### 3. Customer Satisfaction Distribution

Nearly 30% of tickets have an unknown satisfaction rating, limiting confidence in performance measurement.

Among recorded responses, satisfaction levels are polarized, with more users reporting either highly satisfied or unsatisfied experiences.

![Satisfaction Distribution](images/satisfaction_distribution.png)

---

## Business Recommendations

- Reduce recurring ticket drivers in Systems and Access/Login through targeted system improvements
- Establish service-level expectations for low-priority tickets to prevent backlog growth
- Audit long-running high-priority tickets to identify workflow breakdowns
- Improve satisfaction survey completion rates to strengthen customer experience measurement

---

## What This Project Demonstrates

- Operational performance analysis
- KPI evaluation (resolution time, backlog, CSAT)
- Ability to connect operational metrics to customer outcomes
- Executive-focused recommendation development
- Dashboard creation and data storytelling using Power BI

---

## Future Improvements

Future analysis could include:

- Root-cause analysis of unsatisfied tickets
- Channel-based breakdown of ticket resolution efficiency
- Predictive modeling for ticket resolution time
- Automated satisfaction tracking improvements
