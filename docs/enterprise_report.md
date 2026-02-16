# Enterprise Help-Desk Performance Analysis Report

---

## Overview

This enterprise-level report analyzes 100,000 cleaned help-desk tickets to evaluate operational efficiency and its impact on customer satisfaction. The analysis identifies high-volume support areas, resolution bottlenecks, backlog accumulation, and gaps in customer feedback collection.

The goal is to provide executive-ready insights that support faster resolution times, improved customer satisfaction, and scalable service operations.

---

## Business Problem

Support teams must balance speed, prioritization, and quality of service. Without clear visibility into resolution patterns and satisfaction trends, inefficiencies can grow unnoticed.

> **Primary Question:**  
> How can the company improve the speed and effectiveness of help-desk issue resolution to increase customer satisfaction and support future growth?

---

## Dataset

The dataset contains 100,000 help-desk tickets. Each record includes:

- Functional area (Filed Against)
- Priority level
- Days open (resolution time)
- Customer satisfaction rating

This dataset connects operational metrics directly to customer outcomes.

---

## Data Preparation

Before analysis, the dataset was cleaned in Microsoft Excel:

- Removed invalid and duplicate records  
- Standardized categorical formats  
- Handled missing values  
- Validated resolution time entries  

The cleaned dataset was then imported into Microsoft Power BI for visualization and analysis.

Power BI dashboards were created to evaluate:

- Ticket volume by functional area  
- Average resolution time by priority level  
- Maximum resolution time by priority level  
- Satisfaction distribution patterns  

---

## Operational Analysis

### 1. Ticket Volume by Functional Area

- **Systems:** 40,035 tickets  
- **Access/Login:** 29,921 tickets  
- **Software:** 20,068 tickets  
- **Login:** 9,976 tickets  

Systems generates the highest workload, followed by Access/Login. These two areas account for the majority of support demand.

![Tickets by Function](../images/tickets_by_function.png)

**Business implication:**  
Operational improvements in Systems and Access/Login will produce the largest impact on workload reduction and customer satisfaction.

---

### 2. Resolution Time by Priority Level

**Maximum Days Open**
- Level 3 (High Priority) contains the longest-running outliers.

**Average Days Open**
- Level 1 (Low Priority): 8 days  
- Level 3 (High Priority): 6 days  

This reveals three patterns:

- High-priority tickets are resolved faster on average  
- Low-priority tickets accumulate and create backlog  
- A small number of high-priority tickets remain open unusually long  

![Days Open by Priority](../images/days_open_by_priority.png)

![Max Days Open by Priority](../images/max_days_open_by_priority.png)

**Business implication:**  
Service-level expectations should be established for low-priority tickets. High-priority outliers require workflow review.

---

### 3. Satisfaction Levels by Functional Area

Across all functional areas:

- **0 – Unknown** is the largest category  
- **3 – Highly Satisfied** is second  
- **1 – Unsatisfied** follows  
- **2 – Satisfied** is the smallest group  

![Satisfaction and FA Distribution](../images/satisfaction_column_chart.png)

**Interpretation:**

- A significant portion of customers do not complete surveys  
- Respondents tend to be highly satisfied or highly dissatisfied  
- Neutral experiences may be underreported  

---

### 4. Overall Satisfaction Distribution

- **Unknown:** 30.21%  
- **Highly Satisfied:** 29.06%  
- **Satisfied:** 19.60%  
- **Unsatisfied:** 21.12%  

![Satisfaction Distribution](../images/satisfaction_distribution.png)

**Business implication:**

- Survey non-response reduces reliability of performance measurement  
- The 21.12% unsatisfied segment should be analyzed for common drivers  
- The highly satisfied group may reveal repeatable best practices  

---

## Business Recommendations

- Prioritize Systems and Access/Login process improvements  
- Implement service-level expectations (SLEs) for low-priority tickets  
- Audit long-running high-priority tickets  
- Improve satisfaction survey completion rates  
- Analyze unsatisfied tickets for recurring patterns  

---

## What This Report Demonstrates

- Large dataset operational analysis (100,000 records)  
- KPI evaluation (resolution time, backlog risk, CSAT)  
- Identification of workflow inefficiencies  
- Executive-level data storytelling using Power BI  
- Translation of metrics into strategic recommendations  

---
