💳 Credit Card Fraud Detection & Risk Analysis
📌 Project Overview
This project addresses the critical challenge of identifying fraudulent financial transactions in a highly imbalanced environment. Using a dataset of 284,807 transactions with a fraud rate of only 0.17%, I developed a machine learning solution that prioritizes "Recall" to ensure 4 out of 5 fraudulent activities are captured, while providing a risk-based alert system for manual review teams.

📊 Interactive Risk Dashboard
To provide business-level visibility, I designed an interactive Power BI Dashboard with a modern Glassmorphism aesthetic.

![Fraud Detection Analysis Dashboard]
<img width="1444" height="810" alt="Screenshot 2026-04-06 165422" src="https://github.com/user-attachments/asset![Uploading Screenshot 2026-04-06 165422.png…]()
s/8623ff47-55b6-4e8a-8bf5-8d0a897a7359" />

Figure 1: Risk Tier Analysis, Temporal Fraud Trends, and Model Performance Overview.

🛠️ Technical Stack
Language: Python (Pandas, NumPy)

Machine Learning: Scikit-learn, SMOTE (Synthetic Minority Oversampling Technique)

Visualization: Power BI (DAX, Neon UI Design), Matplotlib, Seaborn

Database: SQL (Data Discovery & Validation)

🚀 STAR Methodology (Project Deep-Dive)
Situation
The dataset was extremely skewed (578:1 ratio of legitimate to fraudulent transactions). Standard accuracy was a "trap"—a model could be 99.8% accurate while failing to catch a single fraud case.

Task
Develop a classification system that handles extreme imbalance, maximizes Recall (to catch fraud), and categorizes transactions into actionable risk tiers for the operations team.

Action
Preprocessing: Cleaned and scaled 30 PCA-transformed features using Python.

Handling Imbalance: Implemented SMOTE to oversample the minority class, ensuring the model learned fraud patterns effectively.

Modeling: Built a Random Forest classifier, tuning hyperparameters to optimize for the F1-score and Recall.

UI/UX Design: Developed a 4-tier risk classification (Low, Medium, High, Critical) and visualized it in a sleek, dark-mode Power BI dashboard.

Result
Recall Improvement: Boosted fraud detection recall from 61% to 81.6%.

Precision: Maintained a high precision of 94.1% to minimize false positives.

Business Impact: The automated risk-tier system is projected to reduce the manual fraud review workload by ~60%.

📈 Key Insights & Features
Fraud by Hour: Identified specific time windows where fraudulent activity spikes, allowing for targeted security monitoring.

Amount Bins: Discovered that while fraud occurs at all levels, a significant volume of "High Risk" cases occurs in specific low-to-mid value transaction brackets.

Automated Reporting: Integrated the Python model output into Power BI to replace manual risk assessment.
