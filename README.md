# **📊 Bank Telephonic Marketing: Subscription Prediction**

![Power BI Dashboard](images/dashboard_overview.png)  
*Above: Power BI Dashboard showcasing key campaign insights.*

---

## **🔗 Overview**
Predict customer subscription to term deposits using telephonic marketing data. This project leverages machine learning and data visualization to improve campaign targeting.

---

## **📈 Key Insights**
- **Subscription Rates**: ~11% of customers subscribe.
- **Call Duration**: Longer calls correlate with higher subscriptions.
- **Age & Job Type**: Critical factors influencing subscriptions.

![Customer Insights](images/customer_insights.png)  
*Demographics and behavior trends impacting outcomes.*

---

## **🗂 Dataset**
- **Train**: 40,000 rows, 17 columns.
- **Test**: 5,211 rows, 16 columns.
- **Target**: `y` (yes/no subscription).

---

## **🤖 Model Performance**

| **Model**           | **Accuracy** | **F1 Score** | **Notes**                 |
|----------------------|--------------|--------------|---------------------------|
| Logistic Regression  | 93.4%        | 0.34         | Baseline                  |
| Random Forest (Tuned)| 92.2%        | 0.58         | Best performance achieved |
| SMOTETomek + RF      | 91.8%        | 0.53         | Improved recall           |

---

## **📊 Dashboard Insights**
- **Demographics**: Age and job type are strong predictors.  
- **Call Duration**: Effective engagement drives subscriptions.  
- **Contact Month**: Subscriptions peak in May and October.

![Dashboard Insights](images/dashboard_trends.png)

---

## **📌 Results**
- **Best Model**: Random Forest with hyperparameter tuning (F1 Score: 0.58).  
- **Test Predictions**: Exported in `KeyCode.csv` for leaderboard submission.

![Streamlit App](images/streamlit_app.png)  
*Streamlit app for predictions and insights.*

---

## **🔮 Future Enhancements**
- Implement advanced models like LightGBM and CatBoost for better accuracy and F1 Score.
- Automate feature engineering for efficiency and consistency.
- Deploy the solution in a cloud environment for real-time predictions.

---

## **👥 Group Members**
1. **Krishna**  
   - [LinkedIn](https://www.linkedin.com/in/krushna-chandra-nayak-b18a55176/)  
   - Email: krishnaintoit@example.com

2. **Nisha**  
   - [LinkedIn](https://www.linkedin.com/in/nisha-rana-185189216/)  
   - Email: nisharanakv123@gmail.com

3. **Akash**  
   - [LinkedIn](https://www.linkedin.com/in/ananya-example)  
   - Email: akashvishwakarmaav84@gmail.com

---
