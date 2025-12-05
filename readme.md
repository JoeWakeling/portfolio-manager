# 📊 ML Portfolio Tracker & Tuner

> A smart, machine learning–powered portfolio allocator with a sleek React Native mobile interface.

## 🧠 Features
- 🧮 Risk-based ML portfolio optimization using historical financial data
- 🧠 Predictive modeling trained on the U.S. 2022 Survey of Consumer Finances (SCF)
- 📱 React Native mobile app for real-time portfolio monitoring and strategy planning
- 📊 Interactive charts for asset allocation, performance, and market trends
- ⚡ Live financial data integration for market-aware insights

## 🧪 Final Model Results
### 📈 Predictive accuracy
| **Evaluation Metric** | **Score Before Tuning**<br>(Training Set 10-Fold CV Mean) | **Score After Tuning**<br>(Training Set 10-Fold CV Mean) | **Score After Tuning**<br>(Test Set) |
| --------------------- | --------------------------------------------------------- | -------------------------------------------------------- | ------------------------------------ |
| **R²**                | 0.8296                                                    | 0.8349                                                   | 0.8395                               |
| **-RMSE**             | -0.1297                                                   | -0.1282                                                  | -0.1277                              |
| **-MSE**              | -0.0174                                                   | -0.0172                                                  | -0.0163                              |
| **-MAE**              | -0.0528                                                   | -0.0524                                                  | -0.0519                              |

### 📊 Feature Importances
![Home](assets/results/feature-importances.png)

## 🚀 App Screenshots

<p align="center">
  <img src="assets/screens/home.jpg" width="220" />
  <img src="assets/screens/insights.png" width="220" />
  <img src="assets/screens/questionnaire.png" width="220" />
</p>
<p align="center">
  <img src="assets/screens/invest.png" width="220" />
  <img src="assets/screens/invest2.jpg" width="220" />
  <img src="assets/screens/invest3.jpg" width="220" />
</p>
<p align="center">
  <img src="assets/screens/markets.png" width="220" />
  <img src="assets/screens/markets2.png" width="220" />
</p>

## 🛠️ Tech Stack

### 🧩 Frontend
- React Native
- Expo
- Tailwind CSS
- Firebase (auth, database)

### 🔬 Backend & ML
- Python, Flask (API server)
- scikit-learn, NumPy, pandas, matplotlib
- Supervised regression model for portfolio optimization and user risk profiling

### 📡 Data Sources
- Yahoo Finance API
- MoneySavingExpert (investment options)

---
