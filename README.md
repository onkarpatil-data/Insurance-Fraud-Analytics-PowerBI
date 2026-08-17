# 📊 Insurance & Fraud Analytics Dashboard

An interactive **Power BI Dashboard** developed to analyze insurance claims, customer policies, claim amounts, and fraudulent activities.

---

## 🚀 Project Overview

The **Insurance & Fraud Analytics Dashboard** provides an interactive view of insurance data and helps analyze:

- Insurance claim performance
- Policy and customer information
- Claim severity
- Claim amounts
- Fraud cases
- Fraud percentages
- Customer demographics
- Vehicle-related claims
- Factors associated with fraudulent claims

The dashboard contains **4 pages**:

1. 🏠 Start
2. 📈 Executive Overview
3. 📋 Claim Analysis
4. 🚨 Fraud Analysis

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Data Visualization**
- **Microsoft Excel / CSV Dataset**

---

## 📂 Dataset

The dashboard is created using an insurance dataset containing approximately **1,000 records**.

The dataset contains information related to:

- Policy Number
- Customer Age
- Policy State
- Policy Bind Date
- Incident Date
- Incident State
- Incident Type
- Incident Severity
- Claim Amount
- Vehicle Information
- Customer Relationship
- Fraud Reported
- Witnesses
- Police Report Availability
- Property Damage
- Other Insurance Attributes

> **Note:** The dataset should only be uploaded if you have permission to redistribute it.

---

# 📊 Dashboard Pages

## 1. 🏠 Start Page

The Start page acts as the landing page of the dashboard.

It provides navigation to:

- Executive Overview
- Claim Analysis
- Fraud Analysis

---

## 2. 📈 Executive Overview

The Executive Overview provides a high-level summary of insurance performance.

### Key Performance Indicators

- **Total Claim Amount:** 53M
- **Total Policies:** 1000
- **Fraud Cases:** 247
- **Fraud Percentage:** 24.70%
- **Average Claim:** 52.76K
- **Average Premium:** 1.26K

### Visualizations

- Claim Amount by Incident Type
- Total Claims by Incident State
- Average Claim by Gender
- Claims by Incident Severity
- Total Claim Amount by Month

---

## 3. 📋 Claim Analysis

The Claim Analysis page focuses on detailed analysis of insurance claims.

### Key Performance Indicators

- **Total Claim Amount:** 15M
- **Average Claim:** 56.39K
- **Total Injury Claim:** 2M
- **Total Property Claim:** 2M
- **Total Vehicle Claim:** 11M

### Visualizations

- Total Claim Amount by Occupation
- Number of Policies by Gender
- Total Claim Amount by Relationship
- Fraud % by Hobbies
- Total Claim Amount by Auto Make

---

## 4. 🚨 Fraud Analysis

The Fraud Analysis page focuses on identifying and understanding fraudulent insurance claims.

### Key Performance Indicators

- **Total Customers:** 1000
- **Average Age:** 39
- **Fraud Cases:** 247
- **Fraud Percentage:** 24.70%
- **Total Fraud Claim Amount:** 15M

### Visualizations

- Total Claim Amount by Year/Month
- Fraud % by Property Damage
- Fraud % by Witnesses
- Fraud % by Police Report Availability
- Top Policies by Fraud Claim Amount

---

# 📸 Dashboard Preview

## Executive Overview

![Executive Overview](screenshots/executive-overview.png)

## Claim Analysis

![Claim Analysis](screenshots/claim-analysis.png)

## Fraud Analysis

![Fraud Analysis](screenshots/fraud-analysis.png)

---

# 📐 DAX Measures

The project uses DAX measures to calculate important business metrics such as:

```DAX
Average Claim
Total Claim Amount
Total Claims
Total Policies
Fraud Cases
Fraud %
Fraud Claim Amount
Genuine Claims
Total Injury Claim
Total Property Claim
Total Vehicle Claim
