## Live Dashboard

🔗 https://haodata.github.io/Walmart-Sales-Forecasting/

# Walmart-Sales-Forecasting

## Project Overview

Walmart Sales Forecasting is a machine learning project designed to predict future retail sales across multiple Walmart stores and departments. The objective is to help businesses improve inventory planning, workforce allocation, revenue forecasting, and operational decision-making through data-driven insights.

The project explores historical sales data and compares multiple deep learning approaches to identify the most effective forecasting model for retail demand prediction.

---

## Business Problem

Accurate sales forecasting is critical for modern retail operations because it directly impacts:

* Inventory optimization
* Demand planning
* Workforce scheduling
* Revenue forecasting
* Supply chain management

Retailers experience seasonal fluctuations, holiday effects, promotional impacts, and changing customer behavior. This project aims to provide reliable forecasts that help businesses make informed operational and strategic decisions.

---

## Dataset

### Source

Walmart Recruiting – Store Sales Forecasting

### Dataset Statistics

* 421,570 weekly sales records
* 45 Walmart stores
* 81 departments
* Historical sales transactions
* Holiday indicators
* Store-level information
* Department-level information
* Economic and seasonal factors

---

## Technologies Used

### Programming

* Python

### Data Analysis

* Pandas
* NumPy

### Data Visualization

* HTML
* CSS
* JavaScript
* SVG Charts

### Machine Learning

* GRU (Gated Recurrent Unit)
* Refined GRU
* LSTM
* Deep Neural Networks

### Development Environment

* Jupyter Notebook
* Google Colab

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Preparation
6. Model Development
7. Model Evaluation
8. Sales Forecast Generation
9. Dashboard Development
10. Business Insight Analysis

---

## Key Features

* Weekly sales forecasting
* Deep learning-based prediction models
* Trend analysis
* Seasonal pattern detection
* Holiday impact analysis
* Interactive dashboard
* Model performance comparison
* Business intelligence reporting

---

## Models Evaluated

The project compares multiple forecasting architectures:

### Standard GRU

Baseline recurrent neural network model used for sales forecasting.

### Refined GRU

Enhanced GRU architecture with optimized training configuration and improved forecasting stability.

### LSTM

Long Short-Term Memory network designed to capture long-term temporal dependencies in retail sales data.

---

## Model Performance

The following metrics were used to evaluate model performance:

* WMAE (Weighted Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)
* MAPE (Mean Absolute Percentage Error)

### Best Model

🏆 Refined GRU achieved the strongest performance among all tested architectures.

**Best WMAE: $13,627**

The Refined GRU demonstrated improved forecasting accuracy and stability compared with both the standard GRU and LSTM models.

---

## Interactive Dashboard

The project includes a multi-page interactive dashboard designed to support business analysis and decision-making.

### Dashboard Pages

#### Executive Overview

* Sales summary
* KPI monitoring
* Business insights

#### Store Analysis

* Store-level performance comparison
* Sales trend exploration
* Regional analysis

#### Model Performance

* Forecast accuracy evaluation
* Model comparison
* Error analysis

#### Forecast Dashboard

* Future sales predictions
* Historical vs predicted sales
* Forecast visualization

### Dashboard Features

* Interactive filtering
* Store selection
* Department analysis
* Model comparison
* Historical backtesting
* Performance monitoring

---

## Business Impact

This forecasting system can help retailers:

* Improve inventory planning
* Reduce stock shortages
* Optimize staffing decisions
* Improve demand forecasting
* Support data-driven business strategies

---

## Results

The forecasting system successfully identified:

* Seasonal sales fluctuations
* Holiday-driven demand spikes
* High-performing stores
* High-performing departments
* Long-term sales trends

The project demonstrates how machine learning and business intelligence techniques can be combined to generate actionable retail insights.

---

## Future Improvements

Potential enhancements include:

* Real-time forecasting
* Automated model retraining
* Cloud deployment
* API integration
* Retail ERP integration
* Advanced Transformer-based forecasting models
* Additional economic indicators (CPI, Fuel Price, Promotions)

---

## Repository Structure

```text
Walmart-Sales-Forecasting/
│
├── data/
├── notebooks/
├── models/
├── dashboard/
├── screenshots/
├── README.md
├── requirements.txt
└── app.py
```

---

## Author

Wenhao Li

Data Analyst | Business Intelligence | Python | SQL | Machine Learning

GitHub:
https://github.com/haodata

LinkedIn:
https://www.linkedin.com/in/wenhao-li-799a941a9/
