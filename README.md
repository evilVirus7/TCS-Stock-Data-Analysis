# 📊 TCS Stock Data Analysis Project  
### End-to-End Financial Data Analytics Case Study  

![TCS Stock Banner](assets/tcs_banner.png)

---

## 🔍 Project Overview  

This project presents a **complete end-to-end data analytics workflow** focused on analyzing the historical stock performance of **Tata Consultancy Services (TCS)**.

Built as part of my **Data Analytics Internship**, this repository demonstrates how real-world financial data is handled—from raw datasets to insights and dashboards. The project emphasizes **clarity, analytical thinking, and business relevance**, avoiding unnecessary complexity while maintaining professional depth.

⚠️ This project is **educational and analytical**, not intended for trading or financial advice.

---

## 🎯 Objectives  

- Analyze historical stock price behavior of TCS  
- Perform data cleaning and validation  
- Conduct Exploratory Data Analysis (EDA)  
- Identify price trends and trading behavior  
- Engineer analytical features (Moving Averages, Returns)  
- Build a basic predictive model  
- Present insights using Python and Power BI  

---

## 🧠 Business Context  

Tata Consultancy Services (TCS) is one of India’s largest IT services companies and a key component of major stock market indices. Analyzing its stock performance helps in understanding:

- Long-term growth trends  
- Market volatility and recovery patterns  
- Investor participation and trading dynamics  

Such analysis is valuable for analysts, investors, and financial institutions.

---

## 📁 Dataset Description  

The project uses historical daily stock data containing:

- **Date** – Trading date  
- **Open** – Opening price  
- **High** – Highest price of the day  
- **Low** – Lowest price of the day  
- **Close** – Closing price  
- **Volume** – Number of shares traded  
- **Dividends** – Dividend values (if any)  
- **Stock Splits** – Stock split information  

The dataset spans multiple years, making it suitable for long-term trend analysis.

---

## 🛠️ Tools & Technologies  

- **Programming Language:** Python  
- **Libraries:**  
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  
- **Environment:** Jupyter Notebook / VS Code  
- **Dashboarding Tool:** Power BI  

---

## 🧹 Data Preparation  

Key preprocessing steps:

- Converted date column to datetime format  
- Sorted data chronologically  
- Verified numerical data types  
- Checked for missing values (none found)  
- Ensured consistency in financial figures  

Clean data = credible insights.

---

## 📈 Exploratory Data Analysis (EDA)  

### 📌 Stock Price Trend Analysis  
- Strong long-term upward trend  
- Visible volatility during major market events  
- Consistent recovery after downturns  

### 📌 Trading Volume Analysis  
- Frequent volume spikes during volatile periods  
- High volume does not always indicate sharp price movement  

➡️ Suggests institutional and long-term investor activity.

### 📌 Correlation Analysis  
- Open, High, Low, Close prices are highly correlated  
- Trading volume shows weak correlation with price  
- Corporate actions have minimal short-term impact  

---

## ⚙️ Feature Engineering  

Additional features were created to improve analysis:

- **30-Day Moving Average** – Short-term trend detection  
- **100-Day Moving Average** – Long-term trend identification  
- **Daily Returns** – Volatility and risk assessment  

Daily returns are centered around zero with occasional extreme values, reflecting real-world market shocks.

---

## 🤖 Predictive Modeling  

A **Linear Regression model** was implemented to estimate the closing price.

**Model Inputs:**  
- Open Price  
- High Price  
- Low Price  
- Trading Volume  

**Target Variable:**  
- Closing Price  

**Model Performance:**  
- R² Score ≈ 0.99  
- Low Mean Squared Error (MSE)  

⚠️ High accuracy is driven by strong correlation among price variables. The model is for learning purposes only.

---

## 💡 Key Insights  

- TCS demonstrates strong long-term growth and resilience  
- Price-based features are strong predictors of closing price  
- Trading volume alone is not a reliable indicator  
- Simple models explain historical patterns but not future uncertainty  

---

## 🚧 Limitations  

- No macroeconomic or sentiment data included  
- Advanced time-series models not explored  
- Not suitable for real-time trading decisions  

These limitations were intentional to keep the project focused and realistic.

---

## 🔮 Future Scope  

- Implement ARIMA / LSTM time-series forecasting  
- Add macroeconomic indicators and news sentiment  
- Perform volatility analysis (VaR, drawdown)  
- Enhance dashboards with interactivity  
- Automate data ingestion using APIs  

---

## 📊 Power BI Dashboard  

![Power BI Dashboard](assets/powerbi_dashboard.png)

An interactive dashboard was built using Power BI to visualize trends, volume behavior, and key insights.

---

## 📂 Repository Structure  

├── data/
│ ├── TCS_stock_history.csv
│ ├── TCS_stock_info.csv
│ └── TCS_stock_action.csv
│
├── notebooks/
│ └── TCS_Stock_Data_Analysis_Project.ipynb
│
├── dashboard/
│ └── TCS Stock Data Analysis Dashboard.pbix
│
├── reports/
│ ├── TCS Stock Data Analysis – Project Report.pdf
│ └── TCS Stock Analysis Project Presentation.pptx
│
├── requirements.txt
└── README.md