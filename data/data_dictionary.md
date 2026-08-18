# Data Dictionary — Telco Customer Churn

| Column | Type | Description | Example Values |
|---|---|---|---|
| customerID | string | Unique customer identifier | 7590-VHVEG |
| gender | categorical | Customer's gender | Male, Female |
| SeniorCitizen | binary | Whether customer is a senior citizen | 0, 1 |
| Partner | categorical | Whether customer has a partner | Yes, No |
| Dependents | categorical | Whether customer has dependents | Yes, No |
| tenure | numeric | Number of months customer has stayed | 0–72 |
| PhoneService | categorical | Whether customer has phone service | Yes, No |
| MultipleLines | categorical | Whether customer has multiple phone lines | Yes, No, No phone service |
| InternetService | categorical | Customer's internet service type | DSL, Fiber optic, No |
| OnlineSecurity | categorical | Whether customer has online security add-on | Yes, No, No internet service |
| OnlineBackup | categorical | Whether customer has online backup add-on | Yes, No, No internet service |
| DeviceProtection | categorical | Whether customer has device protection add-on | Yes, No, No internet service |
| TechSupport | categorical | Whether customer has tech support add-on | Yes, No, No internet service |
| StreamingTV | categorical | Whether customer has streaming TV | Yes, No, No internet service |
| StreamingMovies | categorical | Whether customer has streaming movies | Yes, No, No internet service |
| Contract | categorical | Contract term | Month-to-month, One year, Two year |
| PaperlessBilling | categorical | Whether customer uses paperless billing | Yes, No |
| PaymentMethod | categorical | How the customer pays | Electronic check, Mailed check, Bank transfer, Credit card |
| MonthlyCharges | numeric | Amount charged monthly | $18.25–$118.75 |
| TotalCharges | numeric | Total amount charged over customer lifetime | $0–$8,684.80 |
| Churn | binary (target) | Whether the customer churned | Yes, No |