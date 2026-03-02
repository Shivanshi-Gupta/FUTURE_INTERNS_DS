**Task 02: Customer Retention % Churn Analysis**

**🔍 Project Overview**
This project focuses on analyzing customer churn patterns, identifying key retention drivers, and uncovering customer lifetime trends for a subscription-based business.

The goal was to simulate a real-world SaaS / subscription business scenario, where reducing churn directly impacts revenue, growth, and long-term sustainability.

**🎯 Business Objectives**
Identify why customers are leaving (churn drivers)

Discover which customer segments churn the most

Understand customer lifetime behavior

Quantify revenue leakage due to churn

Detect high-risk customers early

Provide data-backed recommendations to reduce churn and improve retention

**🗂 Dataset Description**

Total Records: 7,043 customers
Features: 21 columns

Category |	Features
Customer |  Info	gender, SeniorCitizen, Partner, Dependents
Service  |	PhoneService, InternetService, StreamingTV, StreamingMovies
Add-on   |	OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport
Contract |	Contract, PaperlessBilling, PaymentMethod
Financial|	MonthlyCharges, TotalCharges
Target	 |  Churn

**⚙️ Tools & Technologies Used**

Python (Pandas, NumPy, Matplotlib, Seaborn)

Google Colab

Power BI (for dashboard & visualization)

GitHub (Version Control & Portfolio Hosting)

**🔎 Key Analysis Performed**
1️⃣ Overall Business Metrics

Total Customers: 7,043

Churned Customers: 1,869

Churn Rate: 26.54%

Average Customer Tenure: 32.37 months

Average Monthly Revenue per User (ARPU): ₹64.76

2️⃣ Churn Pattern Analysis

Very High churn observed in:

0–1 year customers

1–2 year customers

Insight:

Early-stage customers are the most vulnerable, indicating onboarding, engagement, and early experience issues.

3️⃣ Key Churn Drivers (Root Cause Analysis)
Factor                    |  	Impact  |   Business Meaning
Month-to-month contracts  |  Very High|  Customers lack long-term commitment
No Tech Support	          |  High	    |  Lack of service assistance increases dissatisfaction
Fiber optic internet      |  High	    |  Possible pricing or quality dissatisfaction
Electronic check payments |  High	    |  Friction in payment experience

4️⃣ Cohort Retention & Customer Lifetime Trends

Retention drops steeply in early months

Customers who survive beyond 24 months show strong loyalty

Indicates critical early-stage churn window

5️⃣ Revenue Leakage Analysis

Monthly Revenue Lost: ₹1,39,130

Annual Revenue Leakage: ₹16.7 Lakhs

Lifetime Revenue Lost: ₹28.6 Lakhs

Business Meaning:

Even small churn reduction (5–10%) can save lakhs annually, directly boosting profitability.

6️⃣ High-Value Customer Profiling

High-Value Customer Traits:

Feature	Dominant Pattern
Contract	Two-year
Internet Service	Fiber optic
Tech Support	Yes
Payment Method	Credit Card (Auto-pay)

Insight:

Long-term contracts + service add-ons + auto-pay = maximum customer lifetime value

7️⃣ Pricing Sensitivity Analysis
Churn	Avg Monthly Charges
No	₹61.27
Yes	₹74.44

Insight:

Higher pricing significantly increases churn probability → indicates pricing sensitivity.

8️⃣ Early Churn Prediction Logic (High Risk Flag)

High Risk Customers Identified: 966

Churn Probability among High Risk: 65.7%

Normal Customer Churn: 20.3%

Business Use Case:

Enables proactive churn prevention campaigns and targeted retention strategies.

**🚀 Business Recommendations**
🔹 1. Contract Strategy

Push 1-year & 2-year contracts with:

Discounts

Loyalty rewards

Free add-ons

🔹 2. Early Customer Engagement Program

Dedicated onboarding

Early support outreach

Welcome offers in first 90 days

🔹 3. Tech Support Bundling

Offer free trial of Tech Support

Bundle support with premium plans

🔹 4. Pricing Optimization

Introduce tier-based pricing

Offer mid-range affordable plans

🔹 5. Payment Experience Improvement

Promote credit card auto-pay discounts

Incentivize shift away from electronic check

🔹 6. AI-Based Early Churn Detection

Deploy High Risk Flag logic

Trigger retention offers before churn happens
