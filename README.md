# Neo Bank Churn Analysis

## 📌 Overview
This project analyzes customer churn in a neo-bank using transactional and behavioral data.

The objective is to identify key drivers of churn, understand user engagement patterns, and provide actionable recommendations to improve long-term retention.

---

## 🎯 Objectives
- Define churn (30 days of inactivity based on completed transactions)
- Analyze user behavior and engagement patterns
- Identify churn drivers and high-risk segments
- Deliver data-driven business recommendations

---

## 🛠️ Tools & Technologies
- Python (pandas)
- SQL
- Power BI
- GitHub

---

## 📊 Dataset
The dataset includes:
- Users (demographics, plan, activity)
- Transactions (volume, frequency, outcomes)
- Notifications (communication exposure)
- Devices

---

## ⚙️ Data Preparation & Modeling
- Cleaned and structured raw datasets (users, transactions, notifications, devices)
- Defined churn logic based on 30-day inactivity
- Built a **user-level dataset ("user_activity")**
- Engineered key features:
  - Recency (days since last transaction)
  - Frequency (number of transactions)
  - Transaction volume
- Ensured full user coverage, including inactive users

---

## 📊 Power BI Dashboard

### 🔹 Churn by Plan
![Churn by Plan](images/plan_churn.png)

👉 The **Standard plan shows the highest churn**, suggesting weaker engagement at entry level.

---

### 🌍 Churn by Country
![Churn by Country](images/country_churn.png)

👉 Churn varies significantly across countries, highlighting **market-specific behaviors and risks**.

---

### 🏙️ Users and Churn by City
![Churn by City](images/city_churn.png)

👉 High user volume cities do not necessarily have lower churn, indicating **behavioral differences across locations**.

---

## 👩‍💻 My Contribution
- Defined churn logic (30-day inactivity)
- Cleaned and prepared datasets (users, devices)
- Built the **user-level dataset ("user_activity")**
- Performed feature engineering (recency, frequency, volume)
- Developed Power BI dashboards
- Analyzed churn across plans, countries, and cities
- Contributed to insights and business recommendations

---

## 📈 Key Insights
- Low user activity is the strongest predictor of churn
- Standard plan users have significantly higher churn rates
- Churn varies across geographic segments
- Early engagement strongly impacts long-term retention

---

## 💡 Business Recommendations
- Improve onboarding and early user engagement
- Monitor inactivity signals to detect churn risk early
- Optimize notification strategy (avoid under/over exposure)
- Focus retention efforts on high-risk segments

---

## 📌 Project Context
This project was completed as part of a Data Analytics bootcamp (Le Wagon), in a team-based Agile environment.

---

## 📎 Author
**Barbara Le Cornec**  
Junior Data Analyst | Python • SQL • Power BI
