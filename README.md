# Improving Help Desk Resolution Speed and Customer Satisfaction

## Project Overview
This project analyzes help-desk ticket data from IBM Watson Analytics to identify where support issues originate, how long tickets take to resolve, and how these factors impact customer satisfaction. The goal is to provide actionable insights that management can use to improve help-desk efficiency and support future growth.

## Business Question
How can the company improve the speed and effectiveness of help-desk issue resolution to increase customer satisfaction and support future growth?

## Dataset
Each record represents a help-desk ticket and includes:
- Functional area (Filed Against)
- Priority and severity level
- Days open (resolution time)
- Customer satisfaction rating

The dataset combines operational performance metrics with customer experience data to provide a holistic view of help-desk performance.

## Data Preparation
The data was cleaned in Microsoft Excel by removing duplicates, standardizing formats, and handling missing values. The cleaned dataset was then used for analysis and visualization in Power BI.

## Key Insights
### Ticket Volume by Functional Area
Systems and Access/Login generate the highest number of tickets, making them the largest drivers of help-desk workload. These areas should be prioritized for process and system improvements.

![Tickets by Function](images/tickets_by_function.png)

### Resolution Time by Priority
High-priority tickets are resolved faster on average, while low-priority tickets remain open the longest, creating backlogs. A small number of high-priority tickets remain open much longer than expected, indicating potential bottlenecks.

![Days Open by Priority](images/days_open_by_priority.png)

### Customer Satisfaction Gaps
Nearly 30% of tickets have an unknown satisfaction rating, limiting confidence in customer experience insights. Among recorded responses, satisfaction is polarized, with more users reporting highly satisfied or unsatisfied experiences.

![Satisfaction Distribution](images/satisfaction_distribution.png)

## Business Recommendations
- Reduce ticket volume in Systems and Access/Login through targeted process improvements
- Establish service-level expectations for low-priority tickets to reduce backlogs
- Review long-running high-priority tickets to identify workflow bottlenecks
- Improve satisfaction survey completion to ensure reliable customer feedback

## Tools Used
- Microsoft Excel (data cleaning)
- Microsoft Power BI (analysis and visualization)
- GitHub (version control)

## Next Steps
Future work could include deeper analysis of unsatisfied tickets by channel, root-cause analysis of long-running high-priority cases, and improvements to satisfaction data collection.
