{\rtf1\ansi\ansicpg1252\cocoartf2869
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # \uc0\u55357 \u57042  Market Basket Analysis using Apriori\
\
## \uc0\u55357 \u56524  Project Overview\
This project applies Market Basket Analysis (MBA) using the Apriori algorithm to identify products that are frequently purchased together. The goal is to uncover customer purchasing patterns and generate actionable insights that can improve sales strategies, product placement, and targeted marketing.\
\
---\
\
## \uc0\u10067  Business Question\
What items are most commonly purchased together in a single transaction?\
\
---\
\
## \uc0\u55356 \u57263  Objective\
The objective of this analysis is to:\
- Identify frequent itemsets\
- Generate association rules\
- Provide recommendations to improve cross-selling and marketing strategies\
\
---\
\
## \uc0\u55358 \u56800  Methodology\
\
### 1. Data Preparation\
- Removed irrelevant columns (e.g., quantity, region, shipping details)\
- Grouped transactions by order ID\
- Converted dataset into transactional format (True/False)\
\
### 2. Feature Engineering\
- Applied **one-hot encoding** for product presence\
- Used **ordinal encoding** for ordered categorical variables\
\
### 3. Algorithm\
- Applied the **Apriori Algorithm**\
- Generated association rules using:\
  - Support\
  - Confidence\
  - Lift\
\
---\
\
## \uc0\u55357 \u56522  Key Results\
\
One of the strongest association rules discovered:\
\
- **Antecedent:** ALARM CLOCK BAKELIKE GREEN  \
- **Consequent:** ALARM CLOCK BAKELIKE RED  \
- **Support:** 1.13%  \
- **Confidence:** 100%  \
- **Lift:** 88.2  \
\
\uc0\u55357 \u56393  This indicates that customers who purchase the green alarm clock are extremely likely to also purchase the red version.\
\
Additional patterns showed strong relationships between different color variants of the same product line.\
\
---\
\
## \uc0\u55357 \u56481  Business Insights\
\
- Customers frequently purchase **multiple variations of similar products**\
- Strong opportunities exist for:\
  - Product bundling\
  - Cross-selling\
  - Store layout optimization\
\
---\
\
## \uc0\u55357 \u56520  Recommendations\
\
- Bundle frequently purchased items together\
- Place associated products near each other (in-store or online)\
- Use targeted promotions for related products\
- Recommend items during checkout (e.g., \'93Customers also bought\'94)\
\
---\
\
## \uc0\u55357 \u57056 \u65039  Tools & Technologies\
- Python\
- Pandas\
- mlxtend (Apriori Algorithm)\
- Jupyter Notebook\
\
---\
\
## \uc0\u55357 \u56513  Project Structure\
```\
market-basket-analysis/\
\uc0\u9500 \u9472 \u9472  data/\
\uc0\u9500 \u9472 \u9472  notebooks/\
\uc0\u9500 \u9472 \u9472  images/\
\uc0\u9500 \u9472 \u9472  README.md\
```\
\
---\
\
## \uc0\u55357 \u56960  Future Improvements\
- Deploy as a recommendation API using FastAPI\
- Add dashboard visualization (Power BI/Tableau)\
- Test on larger, real-world datasets\
\
---\
\
## \uc0\u55357 \u56526  Author\
Raghe Mahamud  \
- GitHub: https://github.com/raghem  \
- LinkedIn: https://www.linkedin.com/in/raghemahamud/}