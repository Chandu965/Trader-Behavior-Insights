# 🧩 Trader Behavior Insights — Market Sentiment Analysis

### 🎯 Objective
Analyze how Bitcoin's Fear & Greed Index influences trader performance and uncover insights that help design smarter, sentiment-aware trading strategies.

---

### 📊 Data Overview
- **Historical Trading Data:** 211,224 records  
- **Fear & Greed Index:** 2,644 daily sentiment scores  
- **Merged Clean Dataset:** 162,276 records (after outlier removal)

---

### 🧠 Key Insights
- **Model Accuracy:**  
  - Logistic Regression → 70.96%  
  - Random Forest → 77.02%  
- **Top Features Influencing Profitability:**  
  - `Size USD` → 31.7%  
  - `Fee` → 29.5%  
  - `Start Position` → 21.7%  
  - `Sentiment Value` → 17.0%  
- **Correlation (Sentiment vs PnL):** +0.016 → very weak positive  
  - Traders earn slightly higher profits during *Greedy* markets.  
  - Win rate remains steady, but average profit magnitude increases.

---

### 📈 Visual Highlights
| Metric | Observation |
|:--|:--|
| **Win Rate by Sentiment** | Slightly higher in Greed/Neutral conditions (≈30%) |
| **Average PnL** | Rises progressively from Fear → Extreme Greed |
| **Feature Importance** | Trade Size & Fee dominate, Sentiment secondary |

---

### 🧮 Technical Stack
`Python`, `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `scikit-learn`, `Joblib`

---

### 🚀 How to Reproduce
1. Clone this repo  
   ```bash
   git clone https://github.com/Chandu965/Trader-Behavior-Insights.git
