# Consumer App Analytics: Customer Churn & Retention

## 📌 Business Problem
Customer churn is a critical challenge for consumer subscription apps, directly impacting revenue and customer lifetime value. The goal of this project is to identify key behavioral, pricing, and engagement factors that influence churn and translate these insights into actionable product and retention strategies.

## 📊 Dataset
- Consumer subscription customer dataset (~7,000 users)
- Includes:
  - Customer tenure
  - Contract type
  - Monthly charges
  - Feature usage
  - Support availability
  - Churn indicator (Yes/No)

## 🔍 Analysis Approach
- Conducted Exploratory Data Analysis (EDA) to understand customer behavior patterns
- Cleaned and prepared data for analysis and modeling
- Built a Customer 360 view using tenure, pricing, engagement, and support features
- Applied logistic regression to identify key churn drivers with an emphasis on interpretability
- Evaluated model performance using accuracy, recall, and ROC metrics

## 📈 Key Insights
- Customers on month-to-month contracts exhibit significantly higher churn
- New users with short tenure are at the highest risk of churn
- Higher monthly charges increase churn probability when not paired with higher engagement
- Limited support access correlates with increased churn
- Increased feature adoption is associated with lower churn risk

## 🧪 Product & Retention Recommendations
Based on the insights, the following product experiments are recommended:
- **Onboarding optimization** for early-tenure users
- **Contract upgrade incentives** to reduce month-to-month churn
- **Proactive support outreach** for high-risk users
- **Feature bundling experiments** to increase customer engagement

## 🛠 Tools & Technologies
- Python (Pandas, NumPy)
- Machine Learning (Logistic Regression)
- Exploratory Data Analysis (EDA)
- Data Visualization
- Product Analytics Concepts

## 💡 Business Impact
This analysis demonstrates how customer behavior data can be leveraged to:
- Predict churn risk early
- Enable proactive retention strategies
- Improve customer lifetime value
- Support data-driven product and business decisions
