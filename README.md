# Maximizing Revenue for Drivers Through Payment Type <img src="screenshot/Screenshot%2010.png" alt="Screenshot" align="right" width="200"/>

## 📌 Agenda 


* Problem Statement 
* Research Question
* Data Overview
* Methodology Methodology                             
* Analysis and Findings
* Hypothesis Testing
* Recommendations

---

## ❓Problem Statement

In the fast-paced taxi booking sector, making the most of revenue is essential for long-term success and driver happiness. <img src="screenshot/Screenshot%2011.png" alt="Screenshot" align="right" width="100"/>

Our goal is to use data-driven insights to maximise revenue streams for taxi drivers in order to meet this need. Our research aims to determine whether payment methods have an impact on fare pricing by focusing on the relationship between payment type and fare amount. 

---

## 🔍Research Question

* Is there a relationship between total fare amount and payment type?
* Can we nudge customers towards payment methods that generate higher revenue for drivers, without negatively impacting customer experience?

---

## 📊Data Overview

For this analysis, we utilized the comprehensive dataset of NYC Taxi Trip records, used data cleaning and feature engineering procedures to concentrate solely on the relevant columns essential for our investigation. <img src="screenshot/Screenshot%2012.png" alt="Screenshot" align="right" width="600"/>






### Relevant Columns:

* `passenger_count` (1 to 5)
* `payment_type` (card or cash)
* `fare_amount`
* `trip_distance` (miles)
* `duration` (minutes)

---

## 🧪Methodology

### Step 1: Descriptive Analysis

Performed statistical analysis to summarize key aspects of the data, focusing on fare amounts and payment types.

### Step 2: Hypothesis Testing

Conducted a T-test to evaluate the relationship between payment type and fare amount, testing the hypothesis that different payment methods influence fare amounts.

### Step 3: Regression Analysis

Implemented linear regression to explore the relationship between trip duration (calculated from pickup and dropoff times) and fare amount.

---

## 📈Analysis and Findings

### 💳Journey Insights

* Customers paying with cards tend to have a slightly higher average trip distance and fare amount compared to those paying with cash.
* Indicates that customers prefer to pay more with cards when they have high fare amounts and long trip distances.
* <img src="screenshot/Screenshot%2013.png" alt="Screenshot" align="left" width="400"/>
<img src="screenshot/Screenshot%2014.png" alt="Screenshot" align="right" width="250"/>

### 💼Preference of Payment Types

* The proportion of customers paying with cards is significantly higher than those paying with cash.
* Card payments account for 67.5% of all transactions vs. 32.5% for cash.
* This indicates a strong preference for card payments due to convenience, security, or offered incentives.

### 👥Passenger Count Analysis

* Among card payments, single-passenger rides comprise 40.08% of all card transactions.
* Cash payments are also predominantly single-passenger (20.04%).
* Larger groups show a decrease in taxi use or may opt for alternative payment methods.
* These insights emphasize the importance of considering both payment method and passenger count when analyzing transaction data.

---

## 👥Hypothesis Testing

* **Null Hypothesis (H0):** There is no difference in average fare between customers who use credit cards and customers who use cash.
* **Alternative Hypothesis (H1):** There is a difference in average fare between customers who use credit cards and customers who use cash.

**Result:**

* T-statistic = 165.5
* P-value < 0.05

We reject the null hypothesis, suggesting a significant difference in average fare between the two payment methods.

---

## Recommendations

* Encourage customers to pay with credit cards to capitalize on the potential for generating more revenue for taxi cab drivers.
* Implement strategies such as offering incentives or discounts for credit card transactions.
* Provide seamless and secure credit card payment options to enhance customer convenience and adoption.

---

Thank you!
