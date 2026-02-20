# Call Center Performace data 
An Excel project analyzing the monthly operational data from a fictitious call center company to uncover performance trends, customer satisfaction drivers, and service improvement opportunities. The dataset encompasses details such as Customer sentiment & CSAT score, Call reason, Channel, Response time, Call duration, Location, and Call date.

## Table of content
- [Project overview](#Project-overview)
- [Project objective](#Project-objective) 
- [Expected outcome](#Expected-outcome) 
- [Data sources](#Data-sources) 
- [Data cleaning and processing](#Data-cleaning-and-processing)
- [Data analysis and insight](#Data-analysis-and-insight) 
- [Recommendation](#Recommendation) 
- [Conclusion](#Conclusion)


## Project Overview 
This project analyzes October 2020 callcenter operational data to evaluate performance efficiency and customer experience across multiple service channels and locations. Using Microsoft Excel, the analysis focuses on understanding how response time, call reasons, and service channels impact customer satisfaction, sentiment, and overall service quality.

## Project Objective
1. **Performance Analysis**: Understand overall call center performance trends across the year, identifying peak periods, high-demand days, and operational workload distribution.
2. **Operational Efficiency Assessment**: Analyze response time and call duration metrics to identify inefficiencies and areas for service improvement.
3. **Channel & Location Performance**: Evaluate performance across different support channels and locations to determine strengths, weaknesses, and optimization opportunities.
4. **Service Demand Insights**: Assess call reasons and contact patterns to better understand customer needs and improve support strategies

## Expected Outcome
The analysis aims to provide actionable insights, including
- Overall monthly call volume trends.
- Daily call volume patterns and identification of peak service periods.
- Average call duration analysis.
- Identification of top call reasons driving customer contact.
- Channel performance comparison (Phone, Email, Chat, etc.).
- Identification of factors impacting customer satisfaction.
- Location-based performance comparison.
- Recommendations to improve operational efficiency, reduce response time, and enhance customer experience.

## Data Sources
The primary dataset used for this analysis is the "Call Center.csv" file, containing detailed information about each sale made by the company.

## Data Cleaning and Processing
The dataset was cleaned and transformed in Microsoft Excel to ensure accuracy, consistency, and reliability of the analysis. The following steps were carried out:
- Identified and handled missing or blank values
- Standardized date formats
- Structured data for Pivot Table and dashboard reporting
- Cross-checked totals and averages to ensure accuracy

## Data Analysis and Insight 
The primary aim of this analysis is to derive valuable insights from the call center performance data by conducting a comprehensive examination of key operational and customer satisfaction metrics. This multifaceted exploration involves several questions and analyses to better understand patterns, efficiency, and customer experience.

### 1. **How many calls are received each day?**

This analysis evaluates daily call volume by counting the total number of calls received each day using a Pivot Table in Excel.

<img width="691" height="368" alt="Calls per day" src="https://github.com/user-attachments/assets/35da7f14-eba7-4ab3-8b75-88bbbb719704" />

**Findings:**
- The minimum daily call volume recorded was **1,000 calls**.
- The highest number of calls was recorded on **October 21st**, with **1,170 calls**, indicating peak service demand on that day
- **October 31st** recorded only **1 call**, which appears to be an outlier and may require further validation to confirm data accuracy.

**Insight**: Daily call volume remains relatively high throughout the period, with noticeable spikes on specific dates. The unusually low count on October 31st suggests either incomplete data entry or a potential data recording issue.

### 2. Percentage of calls handled within SLA 
SLA (Service Level Agreement) refers to the predefined response time standard that the company commits to when handling customer inquiries. It measures how efficiently customer requests are managed compared to the promised service benchmark.

<img width="476" height="294" alt="Response time" src="https://github.com/user-attachments/assets/503edb10-c564-4901-a98d-5c2ab27bb0c6" />

**Findings:**
- **62%** of calls were handled **within SLA**
- **25%** of calls were handled **below SLA**
- **13%** of calls were handled **above SLA**

  **Insight**: Although a majority of calls (62%) met the agreed service standard, a combined **38% of calls did not meet the ideal timing benchmark**. The 13% exceeding SLA indicates an opportunity to improve staffing allocation, peak-hour planning, or workflow efficiency to enhance overall customer experience.

### 3.  What is the average call duration?
The analysis shows that the **average call duration is 25 minutes**.
This metric represents the typical amount of time an agent spends handling a customer interaction, from the beginning of the call to its resolution

<img width="279" height="62" alt="Call duration" src="https://github.com/user-attachments/assets/81547fbe-2754-4dfe-8d55-bf12a784e3f1" />

**Insight**:

An average call duration of 25 minutes suggests that customer interactions may involve moderate to high complexity, depending on the nature of the call reasons. Longer call durations can indicate:
- Complex customer issues requiring detailed resolution
- High levels of customer engagement
- Potential inefficiencies in call handling processes

### 4. What are the main reasons for customer contact?
The analysis shows that **billing inquiries** were the primary reason customers contacted the call center.

<img width="482" height="289" alt="Reasons for call" src="https://github.com/user-attachments/assets/1b2904ed-5ebe-4b0e-ac37-f0fc315463bd" />

**Findings:**
- **23,462 calls** were related to **billing questions**
- **4,749 calls** were for **payment issues**
- **4,730 calls** were regarding **service outages**

  **Insight**:

Billing-related concerns account for the largest proportion of customer interactions, significantly exceeding other call categories. This indicates that billing processes, clarity of invoices, or payment systems may be generating frequent customer inquiries.

The relatively lower but similar volumes of payment and service outage calls suggest secondary operational areas requiring attention.

From a business perspective, improving billing transparency, enhancing self-service options, and simplifying invoice communication could substantially reduce call volume and improve overall efficiency.

### 5. How does performance differ by support channel?
The analysis examined the distribution of customer interactions across different service channels to understand customer contact preferences.

<img width="672" height="195" alt="Channel" src="https://github.com/user-attachments/assets/0a88c6f4-248e-4ebe-baf3-47236d63f182" />

**Findings**:
- **32% of calls** were made through the **Call Center (Phone Support)**
- **25%** were handled via **Chatbot**
- **23%** were received through **Email**
- **20%** were submitted via the **Web platform**

**Insight**:

Phone support remains the most utilized channel, accounting for the largest share of total interactions. However, digital channels (Chatbot, Email, and Web) collectively represent a significant portion of customer engagement

This indicates a shift toward digital self-service and automated platforms, which may reduce pressure on traditional call center operations.

From a business perspective:
- Enhancing chatbot efficiency could reduce phone traffic further.
- Improving web and email response time may increase customer satisfaction.
- Monitoring CSAT by channel can help determine which platforms deliver the best customer experience.
- Overall, the distribution suggests an opportunity to strategically balance and optimize both traditional and digital support channels.

  ### 6. Are there location-based performance differences?
To determine whether service demand varies by region, call volume was analyzed based on customer location.

<img width="513" height="277" alt="Calls by location" src="https://github.com/user-attachments/assets/4b07b636-db08-49be-93af-98c4c25ad502" />

**Findings**:
- **13,734 calls** were made from **Los Angeles, CA**
- **11,012 calls** were made from **Baltimore, MD**
- **5,419 calls** were made from **Chicago, IL**
- **2,776 calls** were made from **Denver, CO**

**Insight**:

Los Angeles recorded the highest call volume, indicating significantly higher customer engagement or service demand compared to other locations. Baltimore also shows substantial call activity, while Chicago and Denver recorded noticeably lower volumes.

These variations may reflect differences in customer base size, service usage levels, or regional operational issues. Higher call volumes in certain locations may require increased staffing, localized service improvements, or targeted process optimization.

### 7. Customer satisfaction trends
The analysis of customer sentiment reveals a higher proportion of negative feedback compared to positive experiences

<img width="523" height="288" alt="Calls by sentiment" src="https://github.com/user-attachments/assets/2c259e52-fd8f-4fc0-81e5-7c178fe89f7b" />

**Findings**:
- **11,062 customers** expressed **negative sentiment**
- **6,026 customers** expressed **very negative sentiment**
- **8,754 customers** reported **neutral sentiment**
- **3,928 customers** expressed **positive sentiment**
- **3,170 customers** expressed **very positive sentiment**

**Insight**:
The data indicates that negative sentiment responses significantly outweigh positive ones, suggesting potential challenges in service delivery, response efficiency, or issue resolution.

The large volume of neutral responses also suggests opportunities to improve customer interactions and convert neutral experiences into positive ones.

From a business standpoint, improving response time compliance, enhancing agent training, and addressing high-frequency complaint categories (such as billing issues) could help reduce negative sentiment and improve overall customer satisfaction.


## Data visualization

<img width="1342" height="502" alt="DASHBOARD" src="https://github.com/user-attachments/assets/77243db8-953e-496c-9fd8-d31c225d7722" />


## Recommendation 
Based on the analysis of call center performance data, the following recommendations are proposed:
1. **Optimize Staffing During Peak Periods**:Since call volume fluctuates across certain days and months, workforce scheduling should be aligned with high-demand periods to reduce delays and prevent agent overload.
2. **Improve Handling of High-Impact Call Reasons**: Complaint and complex issue calls were more likely to result in lower satisfaction scores. Providing additional training, scripts, and decision support tools to agents can enhance resolution quality.
3. **Strengthen Underperforming Channels**: Channels with lower satisfaction or slower response rates should be reviewed. Process improvements and resource reallocation may help balance performance across all platforms.
4. **Standardize Best Practices Across Locations**: High-performing locations should serve as benchmarks. Their strategies and workflows can be replicated in underperforming regions to ensure consistent service quality.

## Conclusion 
This analysis provided a comprehensive evaluation of the call center’s operational performance and customer satisfaction trends over a one-year period. The findings highlight that response efficiency, call complexity, and channel performance are key factors influencing customer experience.

By implementing data-driven improvements in staffing, response management, and service processes, the organization can enhance operational efficiency, increase customer satisfaction, and build stronger long-term customer relationships.

Overall, this project demonstrates the power of data analytics in supporting strategic decision-making and operational optimization within customer service environments.

Thank you



