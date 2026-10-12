# Telco Customer Retention Analytics

## Overview

Customer churn is an important business concern for telecommunications companies because losing customers can affect retention and future revenue. Understanding how churn varies across customer groups can help businesses identify areas that may require further investigation and targeted retention efforts.

This project uses exploratory and descriptive analytics to investigate customer churn patterns in a telecommunications dataset containing **7,043 customer records**. The analysis examines how churn varies across customer demographics, tenure, contracts, charges, satisfaction, internet services, offers, and geographic locations. Customer-reported reasons for churn are also explored to identify common concerns reported by departing customers.

The objective is to generate business-relevant insights that can inform further investigation into customer retention opportunities.

## Business Questions

The analysis explores the following questions:

* How does churn vary across customer demographic groups?
* How does customer tenure relate to churn?
* How do contract types and payment methods differ across churn groups?
* How do monthly charges and customer value measures relate to churn?
* How does churn vary across internet services and additional service subscriptions?
* How do churn rates differ across offers and geographic locations?
* What reasons do departing customers most frequently report for leaving?

## Tools and Technologies

* **Python** — data analysis and preparation.
* **pandas and NumPy** — data manipulation and numerical analysis.
* **Matplotlib and Seaborn** — data visualisation.
* **Jupyter Notebook** — documenting and presenting the analysis.

## Project Workflow

1. **Data inspection and preparation** — examined the dataset structure, variable types, missing values, and data quality.
2. **Overall churn analysis** — established the baseline churn rate and examined the distribution of churn.
3. **Customer characteristics** — explored relationships between churn and demographic characteristics.
4. **Pricing and customer value** — examined monthly charges, total charges, tenure, and Customer Lifetime Value (CLTV).
5. **Contracts and customer commitment** — compared churn across contract types, tenure groups, and payment methods.
6. **Services and customer engagement** — investigated internet types and additional services.
7. **Offers and retention opportunities** — compared churn rates across offer categories and examined reported reasons for departure.
8. **Geographic analysis** — explored differences in churn across cities and selected customer segments.
9. **Business interpretation** — summarised key findings, potential retention opportunities, and analytical limitations.

## Key Findings

### 1. Overall Churn

The overall churn rate was approximately **26.54%**. This served as the baseline for comparing churn rates across customer groups.

### 2. Customer Tenure

Customers in their first 12 months had an observed churn rate of approximately **47.4%**, substantially above the overall baseline. Churn generally decreased across longer-tenure groups.

**Business implication:** The first year of the customer relationship warrants further investigation, particularly around onboarding, service experience, and early retention support.

### 3. Contract Type

Customers on month-to-month contracts had an observed churn rate of approximately **45.8%**. Longer-term contract groups had considerably lower observed churn rates.

**Business implication:** The company could investigate the concerns and needs of month-to-month customers and explore opportunities to improve their retention.

### 4. Customer Satisfaction

Customers with satisfaction scores of 1 or 2 accounted for approximately **77% of all churned customers** (1,440 of 1,869). No churn was observed among customers with satisfaction scores of 4 or 5 in this dataset.

**Business implication:** Low satisfaction scores warrant attention. Further investigation could examine whether dissatisfied customers can be identified earlier and whether appropriate support or service improvements could help address their concerns.

### 5. Internet Type

Fiber Optic customers had a higher observed churn rate than customers using other internet types. They also had a higher average monthly charge.

**Business implication:** Further analysis could examine whether pricing differences, customer experience, or other customer characteristics are associated with the observed pattern.

### 6. Reported Reasons for Churn

Competitor-related reasons accounted for approximately **44.9% of recorded churn reasons**, making them the most frequently reported category. Customers also reported concerns relating to support personnel and service dissatisfaction.

**Business implication:** The company could investigate its competitive position, service quality, and customer support experience to better understand the concerns reported by departing customers.

### 7. Geographic Differences

Churn varied considerably across cities. San Diego had an observed churn rate of approximately **64.9%**, compared with approximately **26.6% in Los Angeles**. Further analysis examined differences across contract types and tenure groups within these cities.

**Business implication:** Locations with elevated observed churn may warrant closer investigation. However, subgroup sizes should be considered before drawing conclusions about individual cities.

## Limitations

* **Observational analysis:** The analysis identifies associations between customer characteristics and churn but does not establish causation.
* **Overlapping characteristics:** Variables such as tenure, contract type, monthly charges, and customer demographics may be related. Descriptive comparisons do not isolate their independent contributions to churn.
* **Customer-reported reasons:** Recorded churn reasons describe responses from departing customers and may not capture every factor associated with their decision to leave.
* **Subgroup sizes:** Some combinations of city, contract type, and tenure contain relatively few customers, which may make their churn rates less stable.
* **Dataset scope:** Findings describe the available dataset and may not generalise to other telecommunications providers, customer populations, or time periods.
* **Customer value interpretation:** CLTV is a predicted customer-value measure based on the dataset's definition. It should not automatically be interpreted as realised revenue or a guaranteed future financial contribution.

## Conclusion

This project examines customer churn through a business analytics perspective, focusing on how churn varies across customer characteristics, contracts, pricing, services, offers, satisfaction, and geography.

The analysis highlights several areas for further investigation, including early-tenure customers, month-to-month contracts, low satisfaction scores, Fiber Optic customers, competitor-related churn reasons, and geographic differences.

Rather than treating these observed patterns as proven causes, the project uses them to identify questions that a telecommunications business could investigate further when developing customer retention strategies.

## Repository Contents

The repository contains the Jupyter Notebook documenting the analysis, along with supporting project files where applicable.

## Data Source

The project uses a telecommunications customer churn dataset containing 7,043 customer records. The dataset has been obtained form Kaggle

## Author

**Adeniran Adelosoye**

Data analytics, data science, and machine learning portfolio project.
