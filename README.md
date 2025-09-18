# 📊 Telecom Customer Churn Analysis & Prediction using Machine Learning  

## 🔍 Project Overview  
Customer churn is a major challenge for telecom companies. Retaining customers is far more cost-effective than acquiring new ones.  
This project applies **data analysis, SQL-based preprocessing, machine learning, and interactive dashboards** to analyze churn behavior, predict at-risk customers, and provide actionable business insights.  

---

## 📂 Project Components  
1. **Data Exploration & Cleaning (SQL)**  
   - Checked data quality (nulls, missing values)  
   - Segmented customers by demographics, contracts, and states  
   - Calculated churn rate and revenue contribution  

2. **Churn Prediction (Python, Jupyter Notebook)**  
   - Feature engineering from customer demographics, services, and billing details  
   - Trained ML model to predict churn probability  
   - Evaluated using accuracy, precision, recall, and ROC curve  

3. **Dashboards (BI Visualization)**  
   - **Churn Prediction Dashboard** → Profiles predicted churners by age, contract, state, payment method, etc.  
   - **Churn Summary Dashboard** → Shows overall churn metrics, churn reasons, and state/service breakdowns.  

4. **Predicted Churners Dataset (CSV)**  
   - Contains customers flagged as high-risk with details such as monthly charges, tenure, refunds, and referrals.  

---

## 📊 Key Insights  
- Overall churn rate: **27%**  
- Highest churn among **customers aged 50+ (31%)**  
- Contracts with the highest churn: **Month-to-Month (46.5%)**  
- Payment method risk: **Mailed Check (37.6% churn rate)**  
- Top churn-prone states: **Jammu (57.2%), Assam (38.1%), Jharkhand (34.5%)**  
- Primary churn reasons: **Competition, Dissatisfaction, Pricing**  

---

## 🛠️ Tech Stack  
- **Languages & Tools**: Python, SQL, Pandas, Scikit-learn  
- **Visualization**: Power BI / Tableau  
- **Database**: SQL Server  
- **Notebook**: Jupyter for model building  

---

## 📂 Repository Structure  
```bash
├── prediction analysis.ipynb          # ML model & churn prediction
├── churned_customers_predictions.csv  # Predicted churners dataset
├── sql queries Backup.md              # SQL queries for data analysis & cleaning
├── Churn Prediction.PNG               # Prediction dashboard
├── Summary.PNG                        # Churn summary dashboard
└── README.md                          # Project documentation
## 📑 Dataset  
source: kaggle

## 📊 Dashboards  

### 🔮 Churn Prediction Dashboard  
![Churn Prediction Dashboard](./dashboards/Churn_Prediction.PNG)  

### 📈 Churn Summary Dashboard  
![Churn Summary Dashboard](./dashboards/Summary.PNG)  


