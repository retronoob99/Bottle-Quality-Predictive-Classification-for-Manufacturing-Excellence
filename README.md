# 🏭Bottle-Quality-Predictive-Classification-for-Manufacturing-Excellence
📌 Project Overview

In manufacturing, even small inefficiencies can lead to significant material waste and cost overruns. This project focuses on predicting Good Footage (production yield) in a bottle manufacturing process using machine learning.

The goal is to identify the most reliable model and understand which operational factors most strongly impact production quality, enabling proactive, data-driven decision-making on the shop floor.

🎯 Problem Statement

Can we accurately predict Good Footage using operational and machine-level data, and determine which factors most influence production performance?

Project Timeline:
Core development completed in December 2025.

## 🔐 Data Confidentiality
Due to a signed **Non-Disclosure Agreement (NDA)**, the original dataset cannot be shared.  
This project demonstrates the complete machine learning workflow while respecting data privacy and confidentiality obligations.

🧾 Dataset & Key Features

The dataset contains manufacturing operation data with the following important features:

Operator Name

Labels Produced

Run Hours

Total Hours

Operation

Press

Press Group

Feet / Hour

🎯 Target Variable:

Good Footage

🤖 Models Implemented

Three machine learning models were trained and evaluated:

Model	Test Accuracy
Support Vector Machine (SVM)	99.27%
XGBoost	99.77% (highest, but excluded due to outlier sensitivity)
Artificial Neural Network (ANN)	99.69%

📌 Although XGBoost achieved the highest accuracy, it was not selected as the final model due to its sensitivity to outliers, which can reduce reliability in real-world manufacturing environments.

✅ ANN was chosen as the best balance between accuracy, stability, and robustness.

📊 Model Accuracy Comparison

The chart below compares the test accuracies of all three models:
<img width="855" height="547" alt="image" src="https://github.com/user-attachments/assets/490ac78c-8570-482c-9934-208f37f45b10" />

🔍 Feature Importance Analysis

Feature importance analysis revealed that Labels Produced is the most influential factor in predicting Good Footage.
<img width="659" height="455" alt="image" src="https://github.com/user-attachments/assets/88223a70-cf10-485f-adf7-d2fd6318e18c" />

🔑 Key Insights:

Labels Produced has the strongest impact on yield

Total Hours and Feet / Hour also play significant roles

Operator and machine-level variables contribute meaningfully to performance variation

💼 Business Impact

This model can help manufacturing teams:

📉 Reduce scrap and rework by predicting low-yield scenarios early

⚙️ Optimize machine workload and throughput

⏱️ Prevent downtime through proactive operational adjustments

💰 Improve profit margins by turning raw production data into actionable insights

🛠️ Tech Stack

Python

Pandas, NumPy

Scikit-learn (SVM implementation, preprocessing, evaluation)

Artificial Neural Networks (ANN)

Support Vector Machine (SVM)

XGBoost

TensorFlow / Keras (Neural Network modeling)

Matplotlib (visualizations)

🚀 Key Takeaways

Built an end-to-end ML pipeline from data preprocessing to model evaluation

Compared multiple advanced models instead of relying on a single algorithm

Prioritized business reliability over raw accuracy

Delivered insights that directly support manufacturing efficiency and quality control

