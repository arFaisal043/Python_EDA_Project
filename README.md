
# Telco Customer Churn Analysis - EDA Project

## 📊 Project Overview
Exploratory Data Analysis (EDA) of telecom customer churn patterns to identify key factors influencing customer attrition.

## 📈 Key Insights
- **Overall Churn Rate**: 26.54% of customers churned
- **High-Risk Groups**: 
  - Senior citizens churn at 41.7% (2x higher than non-seniors)
  - Month-to-month contracts have 42.71% churn rate (15x higher than 2-year contracts)
- **Strong Predictors**: Contract type, customer tenure, and age
- **Not Significant**: Gender shows minimal correlation with churn

## 🔧 Data Processing
- **Dataset**: 7,043 records × 21 features
- **Cleaning**: Fixed TotalCharges column (11 blank entries → 0)
- **Types**: Converted TotalCharges to float64 for analysis

## 📊 Key Visualizations
1. **Churn Distribution** - Overall churn rate
2. **Senior Citizen Analysis** - 2x higher churn rate
3. **Contract Type Impact** - Month-to-month vs. long-term
4. **Tenure Relationship** - New customers churn more

## 🎯 Business Implications
- **Priority**: Focus retention efforts on senior citizens
- **Strategy**: Convert month-to-month to annual contracts
- **Timing**: Target new customers early in lifecycle

## ⚠️ Limitations
- Exploratory analysis only (no predictive modeling)
- Dataset-specific insights

---

*Analysis provides actionable insights for customer retention strategies in telecom.*
```

