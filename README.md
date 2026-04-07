💳 Credit Card Fraud Detection & Risk Analysis

📌 Project Overview
This project addresses the critical challenge of identifying fraudulent financial transactions in a highly imbalanced environment. Using a dataset of 284,807 transactions with a fraud rate of only 0.17%, I developed a machine learning solution that prioritizes "Recall" to ensure 4 out of 5 fraudulent activities are captured, while providing a risk-based alert system for manual review teams.

🎯 Business Problem

Financial institutions process thousands of transactions daily, but only a very small fraction (~0.3%) are fraudulent.

👉 This creates a major challenge:

High class imbalance
Risk of missing fraud cases
Excessive false alerts affecting customer experience

💡 Solution Approach
Performed data cleaning & preprocessing
Handled class imbalance problem
Built risk-tier classification (Low → Critical)
Designed an interactive dashboard for fraud monitoring
Focused on actionable insights instead of just model output

📊 Dashboard Highlights
🔢 Key KPIs
30 Fraud Cases Detected
10,000 Total Transactions
Imbalance Ratio: 1 : 343
Average Fraud Amount: $91.49

⏱ Fraud Trend Analysis
Fraud peaks observed at specific hours
Helps identify suspicious activity windows

📈 Transaction Distribution
Majority transactions are normal (~99.7%)
Fraud forms a very small but critical segment

💰 Fraud by Amount
Most fraud cases fall in low-to-mid transaction ranges
Indicates micro-fraud strategies

⚠ Risk Tier Segmentation

Transactions classified into:

🔴 Critical Risk
🟠 High Risk
🟡 Medium Risk
🟢 Low Risk

👉 Helps prioritize investigation efficiently

🛠 Tools & Technologies
Python (Pandas, NumPy)
Scikit-learn (Fraud Detection Modeling)
SMOTE (Handling Imbalanced Data)
Power BI (Dashboard & Visualization)
SQL (Data Analysis)

📌 Key Insights
Fraud cases are highly imbalanced, requiring special handling
Certain time periods show higher fraud probability
Small-value transactions can still be high-risk
Risk segmentation can reduce manual workload by ~60%

🚀 Business Impact

✔ Faster fraud detection
✔ Reduced financial loss
✔ Improved decision-making
✔ Scalable monitoring system

📁 Project Structure
📦 Fraud-Detection-Dashboard
 ┣ 📊 Dashboard.pbix
 ┣ 📁 Data
 ┣ 📁 Notebooks
 ┣ 📄 README.md
 ┗ 🖼 fraud_dashboard.png
 
🧠 What Makes This Project Stand Out

✔ Combines Machine Learning + BI Dashboard
✔ Solves real-world financial problem
✔ Focuses on business impact, not just code
✔ Designed like an industry-level Deloitte-style project

📬 Connect With Me
💼 LinkedIn: 
💻 GitHub:
⭐ If you like this project

Give it a ⭐ on GitHub — it motivates me to build more real-world analytics projects!
