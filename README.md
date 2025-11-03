# 📞 Telecom Customer Churn Analysis

## 📘 Overview
This project analyzes a telecom company's customer dataset to understand the **factors contributing to customer churn** — i.e., when customers stop using the company's services.  
Using Python, pandas, and visualization libraries, the analysis identifies key drivers behind churn and suggests data-driven strategies to improve customer retention.

---

## 📊 Dataset Information

**Dataset Name:** Telco Customer Churn  
**Total Records:** 7,043  
**Total Features:** 21  

| Feature | Description |
|----------|-------------|
| `customerID` | Unique ID for each customer |
| `gender` | Male or Female |
| `SeniorCitizen` | 1 if customer is a senior citizen, else 0 |
| `Partner` | Whether the customer has a partner |
| `Dependents` | Whether the customer has dependents |
| `tenure` | Number of months the customer has stayed |
| `PhoneService` | Whether the customer has phone service |
| `MultipleLines` | Whether the customer has multiple lines |
| `InternetService` | Type of internet service (DSL/Fiber/None) |
| `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport` | Availability of these online services |
| `StreamingTV`, `StreamingMovies` | Whether customer uses streaming services |
| `Contract` | Contract type (Month-to-month, One year, Two year) |
| `PaperlessBilling` | Whether billing is paperless |
| `PaymentMethod` | Payment type (e.g., Electronic check, Credit card) |
| `MonthlyCharges` | Amount charged monthly |
| `TotalCharges` | Total amount charged |
| `Churn` | Whether the customer churned (Yes/No) |

---

## ⚙️ Tools and Technologies

- **Language:** Python  
- **Environment:** Jupyter Notebook  
- **Libraries Used:**
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn` – Data visualization
  - `scikit-learn` – (optional) For churn prediction models
  - `plotly` – Interactive visualizations

---

## 🔍 Project Workflow

### 1. Data Preprocessing
- Handled missing values and converted `TotalCharges` to numeric.
- Encoded categorical variables.
- Performed feature scaling and correlation analysis.

### 2. Exploratory Data Analysis (EDA)
- Visualized distributions for gender, senior citizens, tenure, and churn.
- Analyzed service usage (Internet, Phone, Security, etc.).
- Explored relationships between contract types, payment methods, and churn.

### 3. Key Insights

| Category | Key Metric | Percentage / Insight |
|-----------|-------------|----------------------|
| **Overall Churn** | — | 26.5% customers churned |
| **Senior Citizens** | 16% | 41% churn rate |
| **Month-to-Month Contracts** | 55% | 43% churn rate |
| **Fiber Optic Users** | 44% | 42% churn rate |
| **Paperless Billing Users** | 59% | 37% churn rate |
| **Customers with Dependents** | 30% | 18% churn rate |
| **Online Security Users** | 28% | 15% churn rate |

---

## 📈 Visual Insights

The notebook includes multiple charts visualizing customer behavior and churn patterns:
- **Gender & Churn Distribution**
- **Contract Type vs Churn**
- **Internet Service vs Churn**
- **Tenure vs Monthly Charges**
- **Correlation Heatmap**

These visuals reveal that **customers with long-term contracts and added services (security, tech support, etc.) have much lower churn rates**.

---

## 💡 Business Recommendations

- Incentivize **long-term contracts** (1–2 years) to reduce churn by up to 60%.  
- Encourage adoption of **Online Security and Tech Support** services.  
- Improve **onboarding experience** for new customers (first 12 months).  
- Offer **discounts or loyalty programs** for high monthly charge customers.  
- Analyze **payment method preferences** — electronic check users churn the most.

---

## 🧠 (Optional) Predictive Modeling
A churn prediction model can be implemented using:
- **Logistic Regression**
- **Random Forest**
- **XGBoost**

Model performance can be evaluated using accuracy, recall, and ROC-AUC metrics.

---

````markdown
## 🚀 How to Run the Project

**Clone the repository:**
```bash
git clone https://github.com/Ismat-stack/telecom_customer_churn.git
cd telecom_customer_churn
````

**Install required dependencies:**

```bash
pip install -r requirements.txt
```

**Run the Jupyter Notebook:**

```bash
jupyter notebook Telecom_Customer_Churn.ipynb
```

---

## 🧾 License

This project is licensed under the **MIT License** — free to use, modify, and share with proper attribution.

---

## 👩‍💻 Author

**Ismat Khan**
📧 **Email:** [ismatafrozkhan121@gmail.com](mailto:ismatafrozkhan121@gmail.com)
💻 **GitHub:** [Ismat-stack](https://github.com/Ismat-stack)
🔗 *Open to collaborations on data analytics, visualization, and machine learning projects.*

```
