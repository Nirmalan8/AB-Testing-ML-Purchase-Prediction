#  A/B Testing + Machine Learning: Predicting Purchases

This project simulates an e-commerce A/B test to evaluate a new homepage design (Group B) versus the old one (Group A), using both statistical and machine learning approaches.

##  Dataset

- 100,000 simulated users
- Features: group (A/B), device, location, age, time on page
- Target: purchase (1 = yes, 0 = no)

##  A/B Testing Analysis

-  Used t-test to check conversion rate difference
-  Found Group B increased purchase rate significantly (p < 0.05)

##  Machine Learning

- Models Used: Logistic Regression & XGBoost
-  XGBoost + `scale_pos_weight` improved recall for buyer class
-  Final model predicts user purchases using behavioral & demographic features

##  Feature Importance
<img width="832" height="463" alt="Screenshot 2025-07-30 093043" src="https://github.com/user-attachments/assets/2ccf18ce-06a2-4d5f-ad86-adc84cf67e67" />

##  Evaluation Metrics (XGBoost)

- Accuracy: 59.8%
- Precision (1): 12%
- Recall (1): 40%
- F1 Score (1): 18%

##  Tools Used

- Python, Pandas, Scikit-learn, XGBoost
- Matplotlib, Seaborn
- Jupyter Notebook

