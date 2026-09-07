# 🏥 Hospital Revenue Cycle Management Dashboard

> An interactive Power BI dashboard designed to analyze hospital Revenue Cycle Management (RCM), claims performance, denials, payments, outstanding balances, and revenue realization.


---

## 📌 Project Overview

This project presents an interactive **Hospital Revenue Cycle Management (RCM) analytics solution built using Microsoft Power BI**.

The dashboard transforms healthcare claims and financial data into actionable insights covering:

* Claims performance
* Claim denial trends
* First-pass claim clearance
* Revenue realization
* Payment performance
* Accounts receivable
* Patient balances
* Insurance performance
* Specialty-level denial analysis

The objective is to help Revenue Cycle teams identify financial leakage, monitor payment performance, and understand the major drivers of claim denials.

> **Note:** This project uses synthetic data and is created for educational and portfolio purposes. It does not contain real patient or confidential healthcare information.

---

## 🎯 Business Problem

Healthcare organizations process a large volume of claims across multiple insurance providers, specialties, and claim statuses.

Without centralized analytics, it can be difficult to identify:

* Where revenue is being lost
* Which claims are being denied
* Why claims are being denied
* Which insurance providers contribute the most to denied revenue
* Which specialties have higher denial exposure
* How efficiently claims are being paid
* How much revenue remains outstanding

This dashboard was developed to provide a centralized analytical view of the Revenue Cycle.

---

## ❓ Business Questions

The dashboard was designed to answer questions such as:

1. What is the total claim volume?
2. What percentage of claims are denied?
3. What percentage of claims are cleared on the first submission?
4. Which denial reasons contribute the most to denied revenue?
5. Which insurance providers have the highest denied amount?
6. Which specialties experience the highest denial exposure?
7. How much revenue has been paid versus the allowed amount?
8. What is the average time taken to receive payment?
9. How much revenue remains outstanding?
10. How does revenue-cycle performance change over time?

---

## 📊 Key KPIs

The dashboard focuses on the following major KPIs:

| KPI                    | Business Purpose                            |
| ---------------------- | ------------------------------------------- |
| Total Claims           | Measures overall claim volume               |
| Claims Denied %        | Measures denial exposure                    |
| First-Pass Clearance % | Measures initial claim quality              |
| Allowed Amount         | Measures expected reimbursable amount       |
| Paid Amount            | Measures realized revenue                   |
| Outstanding Amount     | Identifies unresolved financial exposure    |
| Average Days to Pay    | Measures payment-cycle efficiency           |
| Patient Balance        | Measures outstanding patient responsibility |

---

## 📈 Dashboard Analysis

### 1. RCM Executive Overview

The executive overview provides a high-level summary of claim volume, denial performance, payment realization, and revenue-cycle KPIs.


---

### 2. Denial Analysis

This section focuses on identifying the major drivers of claim denials.

The analysis includes:

* Denial reasons
* Denied amount
* Insurance provider performance
* Specialty-level analysis
* Claim status

---

### 3. Revenue & Payment Analysis

This analysis compares allowed revenue with realized payments and examines payment trends over time.

Key areas include:

* Allowed amount
* Paid amount
* Revenue realization
* Payment trends
* Days to payment


---

### 4. Accounts Receivable Analysis

This section provides visibility into outstanding financial balances and AR exposure.

The analysis helps identify:

* Outstanding claims
* Patient balances
* AR buckets
* Delayed payments
* Revenue requiring follow-up


---

## 🧩 Data Model

The Power BI data model was designed to establish relationships between the core RCM datasets and support efficient filtering and aggregation.


The model incorporates:

* Fact and dimension tables
* Relationships between business entities
* Date-based analysis
* Appropriate filter propagation
* DAX-based analytical measures

---

## 🔎 Interactive Features

The dashboard provides interactive analysis through:

* Slicers
* Cross-filtering
* Drill-down analysis
* Dynamic KPI calculations
* Category-level filtering
* Time-based analysis


---

## 💡 Analytical Insights

The dashboard can be used to identify:

* Major denial drivers
* Insurance providers with higher denial exposure
* Specialties contributing significantly to denied revenue
* Gaps between allowed and paid revenue
* Payment-cycle delays
* Outstanding financial exposure

The purpose is not only to visualize data but also to support **data-driven Revenue Cycle decision-making**.

---

## 🛠️ Tools & Technologies

* Microsoft Power BI
* DAX
* Power Query
* Data Modelling
* Microsoft Excel / CSV
* Data Visualization
* Business Intelligence

---

## ⚙️ Power BI Techniques Demonstrated

* Data cleaning and transformation using Power Query
* Data modelling
* Relationship management
* DAX measures
* KPI calculations
* Time-based analysis
* Conditional formatting
* Interactive slicers
* Cross-filtering
* Drill-down
* Dynamic visual analysis

---

## 📁 Repository Structure

```text
hospital-rcm-powerbi-dashboard/
│
├── dashboard/
│   └── Hospital RCM Dashboard.pbix
│
├── data/
│   └── hospital_rcm_raw_data.xlsx
│
├── screenshots/
│   ├── 01. Kpi's
│   ├── 02. Revenue realization kpi
│   ├── 03. Dax  functions used
│   ├── 04. Dashboard_page-1
│   ├── 05. Dashboard_page-2
│
├── README.md

```


