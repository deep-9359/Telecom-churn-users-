#📉 Telecom-churn-users-
 

An exploratory data analysis (EDA) project to identify key drivers of customer churn in a telecom company using **Python**. The goal is to uncover patterns in customer behaviour and pinpoint which segments are most likely to leave — enabling the business to take proactive retention action.

---

## 🎯 Objective

To analyse a telecom customer dataset and answer:
- What percentage of customers are churning?
- Which customer segments churn the most?
- What contract types, services, and payment methods are linked to higher churn?
- How does tenure affect churn behaviour?



**Key Features Analysed:**
- Demographics: Gender, Senior Citizen status
- Account info: Tenure, Contract type, Payment method
- Services: Phone, Internet, Online Security, Backup, Tech Support, Streaming TV/Movies

---

## 🔍 Key Insights

### 1. Overall Churn Rate
- **26.54%** of customers have churned — roughly 1 in 4 customers

### 2. Senior Citizens Churn More
- Senior citizens show a **comparatively higher churn rate** than non-senior customers despite being a smaller segment

### 3. Tenure is a Strong Predictor
- Customers who churned were mostly those who had used the service for only **1–2 months**
- Long-tenure customers tend to stay — loyalty builds over time

### 4. Contract Type Matters Most
- **Month-to-month contract** customers churn at a significantly higher rate than those on 1-year or 2-year contracts
- Long-term contracts act as a strong retention mechanism

### 5. Services Impact Retention
- Customers **without** OnlineSecurity, TechSupport, and OnlineBackup churn more
- Customers with DSL internet and PhoneService tend to stay longer

### 6. Payment Method is a Signal
- Customers paying via **Electronic Check** are significantly more likely to churn compared to other payment methods

---

## 🛠️ Tools & Libraries Used

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data loading, cleaning, and transformation |
| NumPy | Numerical operations |
| Matplotlib | Custom visualizations and plots |
| Seaborn | Statistical visualizations (countplots, histplots) |
| Jupyter Notebook | Interactive analysis environment |

---

## 📊 Visualizations Included

- Count plot of churned vs retained customers
- Pie chart showing churn percentage split
- Churn by Gender
- Churn by Senior Citizen status (stacked bar chart with percentages)
- Tenure distribution by churn (histogram)
- Churn by Contract type
- Churn across 9 service types (subplot grid)
- Churn by Payment Method

---

## 📌 Project Structure

```
Telecom-churn-analysis/
│
├── data/
│   └── Customer Churn.csv         # Raw dataset
│
├── notebooks/
│   └── TCA.ipynb                  # Main analysis notebook
│
├── screenshots/                   # Visualisation outputs (optional)
│
└── README.md
```

---

## 💡 Business Recommendations

1. **Target month-to-month customers** with loyalty offers or discounts to upgrade to annual contracts
2. **Engage new customers early** — churn spikes in the first 2 months, so onboarding experience is critical
3. **Bundle security & support services** — customers without OnlineSecurity and TechSupport churn more; offer these as default add-ons
4. **Investigate Electronic Check users** — this segment churns most; consider offering incentives to switch to auto-pay methods
5. **Create a Senior Citizen retention programme** — this group churns at higher rates and may need dedicated support

---

## 🚀 How to Run

1. Clone this repository
```bash
git clone https://github.com/deep-9359/Telecom-churn-users-
```

2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the notebook
```bash
jupyter notebook notebooks/TCA.ipynb
```

---

## 👤 Author

**Deepanshu Gautam**
BBA Graduate | Data Analytics Enthusiast
📧 rishabgautam9359@gmail.com
🔗 [GitHub](https://github.com/deep-9359) | 📍 Meerut, Uttar Pradesh
