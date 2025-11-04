# 📈 Sales Forecasting using Regression

## 🧩 Overview
This project predicts future sales using historical data through regression-based machine learning models.  
It demonstrates how data-driven forecasting helps businesses make informed inventory and revenue planning decisions.

**Author:** Akhilesh Kakarla  
**Course:** PGDM – Artificial Intelligence & Data Science  


---

## 🎯 Objective
To build a predictive model that estimates **future sales** based on past performance, marketing spend, and other influencing factors.

---

## 🧱 Tools & Technologies
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **Jupyter Notebook / Google Colab**
- **CSV Dataset** (e.g., sales_history.csv)
- **Linear & Polynomial Regression Models**

---

## 📊 Workflow
1. **Data Collection & Cleaning**  
   - Imported sales dataset (date, region, product, units sold, revenue).  
   - Handled missing values, date formatting, and outlier detection.

2. **Exploratory Data Analysis (EDA)**  
   - Visualized sales trends over time.  
   - Correlation analysis between variables (e.g., Ad Spend vs Sales).  
   - Seasonal and regional patterns identified.

3. **Feature Engineering**  
   - Extracted month, year, and quarter features from the date.  
   - Applied normalization and one-hot encoding where necessary.

4. **Model Development**  
   - Trained regression models:  
     - Linear Regression  
     - Polynomial Regression  
     - Random Forest Regressor (optional for performance comparison)  
   - Evaluated using **R²**, **MAE**, and **RMSE**.

5. **Forecast Visualization**  
   - Created forecast plots comparing actual vs predicted sales.  
   - Highlighted growth trends and expected future demand.

---

## 🧮 Key Results
| Metric | Linear Regression | Polynomial Regression | Random Forest |
|--------:|------------------:|----------------------:|--------------:|
| R² Score | 0.87 | 0.92 | 0.94 |
| RMSE | 1200 | 950 | 800 |

> 📊 Polynomial and Random Forest models achieved higher accuracy in predicting sales trends.

---

## 📘 Deliverables
| File | Description |
|------|--------------|
| `sales_forecasting.ipynb` | Main Jupyter notebook containing full analysis & models |
| `sales_history.csv` | Raw dataset used for training |
| `forecast_results.csv` | Predicted future sales output |
| `README.md` | Documentation of this project |
| `forecast_dashboard.pbix` | (Optional) Power BI dashboard for visualization |


## 🧠 Insights
- Sales show **seasonal spikes** around festive periods.  
- **Marketing Spend** strongly correlates with **Sales Volume**.  
- Future sales expected to grow **10–12%** next quarter based on current trends.

---

## 💾 How to Run
1. Open `sales_forecasting.ipynb` in Jupyter Notebook or Colab.  
2. Install dependencies:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
