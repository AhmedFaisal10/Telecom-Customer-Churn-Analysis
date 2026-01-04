# 📘 Customer Churn Risk Analysis Notes

## 🎯 Objective
To analyze customer churn behavior and identify the primary factors contributing to customer attrition in a telecom business.

---

## 📊 Overall Churn Summary
- Total Customers: 7,043
- Customers at Risk: 1,869
- Overall Churn Rate: ~26.5%

**Insight:** The churn rate is relatively high and requires targeted retention strategies.

---

## 👥 Demographic Analysis
- Gender distribution is nearly balanced, indicating no strong churn dependency.
- Senior citizens represent a smaller portion of customers but show higher churn sensitivity.
- Customers without partners or dependents tend to churn more frequently.

---

## 🧾 Contract & Billing Analysis
- Month-to-month contracts have significantly higher churn compared to long-term contracts.
- Customers with higher monthly charges are more likely to churn.
- Paperless billing and electronic check payments are associated with higher churn risk.

---

## 🌐 Service Usage Analysis
- Fiber optic customers generate higher revenue but also show the highest churn rate.
- Customers without additional services such as tech support or online security churn more often.
- High service expectations increase churn risk when issues occur.

---

## 🕒 Tenure Analysis
- Churn is highest during the first year of subscription.
- Longer-tenure customers are more stable and less likely to churn.

---

## 🎧 Support Ticket Analysis
- Customers with higher numbers of technical tickets are significantly more likely to churn.
- Technical issues are a stronger churn driver than administrative issues.

---

## ⚠️ Data Quality Notes
- Missing values observed in total charges for new customers.
- Churn labels are binary and evenly distributed for modeling purposes.
- Ticket counts were validated for outliers.

---

## 🧠 Final Takeaway
Customer churn is mainly driven by:
1. Short-term contracts
2. High monthly charges
3. Technical service issues
4. Short customer tenure
5. Payment behavior

Addressing these areas can significantly reduce churn and improve customer lifetime value.
