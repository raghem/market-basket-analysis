# 🛒 Market Basket Analysis (Apriori)

## 📌 Overview
This project applies **Market Basket Analysis (MBA)** using the Apriori algorithm to identify products frequently purchased together. The goal is to uncover customer purchasing patterns and provide actionable business insights.

---

## ❓ Business Question
**What items are most commonly purchased together in a single transaction?**

---

## 🎯 Objective
- Identify frequent itemsets  
- Generate association rules  
- Improve cross-selling and marketing strategies  

---

## 🧠 Methodology

### Data Preparation
- Removed irrelevant columns (e.g., quantity, region, shipping)
- Grouped transactions by order ID
- Converted data into transactional format (True/False)

### Feature Engineering
- One-hot encoding for product presence
- Ordinal encoding for ordered categories

### Algorithm
- Apriori Algorithm (mlxtend)
- Metrics used:
  - Support
  - Confidence
  - Lift

---

## 📊 Key Results

| Rule | Support | Confidence | Lift |
|------|--------|-----------|------|
| GREEN → RED Alarm Clock | 1.13% | 100% | 88.2 |

👉 Customers who purchase the green alarm clock are extremely likely to also purchase the red version.

---

## 💡 Business Insights
- Customers frequently purchase multiple variations of similar products  
- Strong cross-selling opportunities exist  

---

## 📈 Recommendations
- Bundle frequently purchased items  
- Place related products near each other  
- Use targeted promotions  
- Implement “Customers also bought” recommendations  

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- mlxtend  
- Jupyter Notebook  

---

## 📁 Project Structure
```
market-basket-analysis/
├── notebooks/
│   └── market_basket_analysis.ipynb
├── README.md
```

---

## 🚀 Future Improvements
- Build a recommendation API (FastAPI)  
- Add dashboard (Power BI / Tableau)  
- Use larger real-world datasets  

---

## 👤 Author
**Raghe Mahamud**  
- GitHub: https://github.com/raghem  
- LinkedIn: https://www.linkedin.com/in/raghemahamud/