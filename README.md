
# Predictive Analytics for Customer Churn

## Goal
Build a SQL + Python pipeline to predict customer churn using historical behavior data.

---

## Deliverables
- **SQL Queries** for feature extraction:
  - Last login date
  - Purchase frequency
  - Average purchase value
  - Churn flag (inactive >90 days)
- **Python Notebook** with:
  - Logistic Regression & Random Forest models
  - Evaluation metrics: ROC curve, precision-recall, confusion matrix
- **Business Interpretation** of churn drivers and retention strategies

---

## Business Questions Answered
1. **Which customers are most likely to churn?**  
   → Customers with low purchase frequency and long inactivity periods.
2. **What behaviors drive churn?**  
   → Lack of recent logins, low purchase value, and reduced engagement.
3. **Which model performs best?**  
   → Random Forest shows higher accuracy and AUC compared to Logistic Regression.
4. **How can churn be reduced?**  
   → Targeted re-engagement campaigns for inactive users, personalized offers for low-frequency buyers.

---

## Insights Summary
- **Churn Drivers:** Inactivity >90 days, low purchase frequency, low average purchase value.  
- **Retention Strategies:**  
  - Personalized discounts for low-frequency buyers.  
  - Loyalty programs to increase engagement.  
  - Proactive outreach to customers nearing churn threshold.  
- **Model Performance:** Random Forest achieved higher precision and recall, making it suitable for churn prediction.

---

