# Customer Segmentation & Predictive Modeling for Marketing ROI Optimization

## 🎯 Project Overview

This project explores a data-driven approach to improve the effectiveness of direct marketing campaigns for a food company. A pilot campaign involving 2,240 customers resulted in a 15.4% success rate and financial loss. This analysis identifies key customer segments and builds predictive models to maximize future campaign profitability and ROI.

---

## 🔍 Business Objective

- Predict which customers are likely to respond to marketing campaigns
- Identify behavioral and demographic characteristics that correlate with purchases
- Improve success rate and reduce financial loss by optimizing target audience

---

## 🧠 Key Insights

- **High-Value Targets**: Younger customers (≤25), single or widowed, no dependents, and higher spenders (> $2,000).
- **Channels**: Web-based and catalog campaigns had better conversion rates.
- **Customer Journey**: Recent and loyal customers responded best.
- **Past Behavior**: Previous positive campaign responses strongly predict future acceptance.

---

## 🛠 Tools & Techniques

- **Languages**: Python (pandas, scikit-learn, matplotlib, seaborn)
- **Statistical Methods**: ANOVA, Chi-square tests
- **Machine Learning**:
  - Decision Tree Classifier
  - Naive Bayes
  - Random Forest (Best performer, ROC-AUC = 0.85)
- **Feature Engineering**: Categorical encoding, segmentation logic
- **Evaluation Metrics**: F1 score, precision, recall, ROC-AUC

---

## 📈 Impact

| Metric                      | Baseline Campaign | With Model |
|----------------------------|-------------------|------------|
| Success Rate               | 15.4%             | 72.2%      |
| Net Profit                 | -2,925 MU         | +3,319 MU  |
| Profit Increase            | —                 | +6,244 MU  |

The predictive model enabled a **56.8% increase in success rate** and turned a loss-making campaign into a profitable one.

---

## 📊 Statistical Highlights

Significant predictors:
- Income
- Recency
- Customer longevity
- Dependencies
- Web purchases
- Total spend

Insignificant predictors (e.g., deal purchases) were excluded to improve model clarity and performance.

---

## 🔍 Dataset

- Sourced from [Kaggle](https://www.kaggle.com/datasets/jackdaoud/marketing-data)
- 2,240 records with customer demographics, spending behavior, and marketing response

---

## 📌 Recommendations

1. Focus future campaigns on high-spending, young, web-active customers with fewer dependents.
2. Leverage insights to design creative, segmented messaging for each audience cluster.
3. Deploy models before campaign rollout to minimize costs and maximize ROI.

---


## 📎 Files in This Repo

- `FoodMarketingAnalysis.ipynb`: Python notebook with EDA, modeling, and evaluation
- `ifood_df.csv`: Cleaned dataset
- `README.md`: Project summary and documentation

---

## 🔄 Future Directions

- Apply time-series and uplift modeling to campaign timing
- Integrate A/B testing simulations
- Develop a customer lifetime value (CLV) model for longer-term strategy
 
