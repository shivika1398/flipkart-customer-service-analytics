# Flipkart — Customer Service Analytics

## 📌 Project Overview

This project analyzes customer service interactions to understand service quality, customer experience, and potential drivers of retention.

The analysis covered **30,000 customer service interactions** across multiple channels, call centers, and contact reasons.

The project evolved from an initial hypothesis-driven analysis into a **measurement and data-quality audit** after testing revealed important limitations in the dataset.

## 🎯 Business Problem

The objective was to investigate whether operational and customer-service factors were associated with customer satisfaction, sentiment, SLA performance, and potential retention-related outcomes.

The analysis examined factors such as:

- SLA compliance
- Customer satisfaction (CSAT)
- Customer sentiment
- Contact channel
- Contact reason
- Call-center performance
- Call duration
- Churn-risk indicators

## 🔍 Analytical Approach

- Defined business questions and measurable KPIs
- Developed a metric tree linking operational metrics to customer outcomes
- Formulated and tested 8 hypotheses
- Evaluated relationships using statistical analysis
- Investigated missing and structurally inconsistent data
- Assessed whether CSAT could be treated as an independent outcome
- Evaluated whether the dataset could support retention analysis
- Reframed the project based on what the data could actually support

## 📊 Key Metrics

- 30,000 customer service interactions
- Average CSAT: 5.54 / 10
- Negative sentiment: 51.8%
- SLA breach rate: 12.7%
- Churn-risk contact rate: 57.9%
- CSAT survey response rate: 37.4%
- Billing-related contacts: 71.4%

## 🧩 Key Findings

### 1. Hypotheses were not supported

The analysis tested 8 hypotheses, but none provided sufficient evidence to establish the proposed relationships.

### 2. CSAT had a structural data-quality issue

The analysis identified that CSAT was structurally related to sentiment, meaning it could not reliably be treated as an independent outcome variable.

### 3. Retention could not be directly measured

The dataset did not contain a persistent customer identifier, repeat-purchase information, tenure, or a direct churn/retention outcome.

Therefore, retention could not be reliably analyzed from the available data.

### 4. Some variables were confounded

Contact reason and channel were not independently distributed, limiting the ability to isolate their effects.

### 5. The analytical conclusion changed

Rather than forcing conclusions from insufficient data, the project was reframed as a **measurement audit** identifying what the existing data could and could not answer.

## 💡 Recommendations

The analysis identified several improvements needed for future customer-service analytics:

- Add a persistent customer ID
- Capture first-contact resolution (FCR)
- Add an agent identifier
- Capture actual response/wait time
- Track transfers and repeat contacts
- Improve CSAT data collection
- Track refunds, credits, reopenings, and follow-ups
- Report missing data explicitly

## ⭐ Project Highlights

- Hypothesis-driven analytical framework
- KPI and metric-tree development
- Statistical hypothesis testing
- Data-quality investigation
- Detection of structural measurement problems
- Transparent handling of inconclusive results
- Translation of analytical limitations into business recommendations

## 🛠️ Skills Demonstrated

**Business Analysis** · **Data Analysis** · **KPI Design** · **Hypothesis Testing** · **Statistical Reasoning** · **Data Quality** · **Customer Analytics** · **Business Problem Solving**

## 👩‍💻 Author

**Shivika Agrawal**

Interdisciplinary Analyst | ECE Engineer | Business & Data Analytics | Research

This project was completed as part of the NextLeap Business Analytics Fellowship.
