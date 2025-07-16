#  Telco Customer Churn Analysis Dashboard

This dashboard provides a comprehensive visual analysis of customer churn in a telecom company. It aims to identify patterns, demographics, and service usage behaviors that contribute to customer retention or churn.

---

<img width="874" height="491" alt="Screenshot 2025-07-16 180838" src="https://github.com/user-attachments/assets/f2bd5eb9-bb8c-48f9-822a-86eb20b1e952" />


##  Objective

The goal of this dashboard is to help stakeholders:

- Understand the profile of customers who have churned vs. those who haven’t.
- Identify patterns in tenure, contract types, payment methods, and demographics.
- Gain insights into which services or customer groups are more likely to churn.

---

##  Key Metrics

- **Total Customers:** `7043`
- **Churned Customers:** `1869`
- **Senior Citizens:**
  - Total: `1142`
  - Among Churned: `476`

---

##  Tenure Distribution

- **All Customers:** Highest customer count observed in tenure range of `0–10` months.
- **Churned Customers:** Most churn occurs within `10–20` months, highlighting early disengagement.

---

## 💳 Payment Method

| Method            | All Customers | Churned Customers |
|------------------|----------------|-------------------|
| Electronic Check | 2365           | 1071              |
| Mailed Check     | 1612           | 308               |
| Bank Transfer    | 1544           | 258               |
| Credit Card      | 1522           | 232               |

> 🔹 **Insight:** Customers using **electronic check** are more likely to churn.

---

## 📃 Contract Type

| Contract Type   | All Customers (%) | Churned Customers (%) |
|-----------------|-------------------|------------------------|
| Month-to-month  | 55.02%            | 88.59%                 |
| One year        | 21.67%            | 8.88%                  |
| Two year        | 23.31%            | 2.57%                  |

> 🔹 **Insight:** Month-to-month contracts are associated with significantly higher churn.

---

## 🌐 Internet Service Type

| Service    | All Customers | Churned Customers |
|------------|---------------|-------------------|
| Fiber Optic| 3096          | 1297              |
| DSL        | 2421          | 459               |
| No Service | 1526          | 113               |

> 🔹 **Insight:** Fiber optic users have the highest churn rate.

---

## 👥 Demographics

- **Gender:** Churn is nearly equal across male and female customers.
- **Senior Citizens:** Overrepresented among churned users.
- **Partner:** Customers **without a partner** tend to churn more.

---

## 🎛️ Filters Available

- **Senior Citizen** (Yes/No)
- Other filters may be applied in the interactive version (e.g., Gender, Contract Type).

---

## 🧠 Key Insights

- Majority churn happens early in the customer lifecycle.
- Month-to-month contracts and electronic payment methods are high churn indicators.
- Fiber optic users are more prone to churn than others.
- Targeted interventions are needed for senior citizens and those without partners.

---

## ✅ Recommendations

- Design onboarding loyalty programs for new users in the first 6–12 months.
- Promote yearly or 2-year contracts through discounts or incentives.
- Focus retention strategies on high-risk groups (e.g., senior citizens, fiber optic users).

---

## 🛠️ Tools Used

- **Visualization:** Power BI
- **Data Source:** Telco Customer Churn CSV
- **Python**

---


---
