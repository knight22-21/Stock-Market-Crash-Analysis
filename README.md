# Market Crash Analysis & Early Warning System

## 📌 Project Overview
This project analyzes historical market crashes using **drawdown analysis** and develops an **Early Warning System (EWS)** based on **rolling statistics of returns and volatility**. By identifying significant downturns and clustering consecutive stress periods, this system aims to provide insights into past crashes and detect early warning signals before major market declines.

---

## 🚀 Features & Methodology
### **1️⃣ Identifying Market Crashes**
- Computed **daily percentage changes** in the market index.
- Measured **drawdowns** (percent drop from the cumulative max).
- Classified major crashes where **drawdown exceeded -20%**.

### **2️⃣ Clustering Consecutive Market Stress Days**
- Grouped **consecutive days of severe drawdowns** into **crash clusters**.
- Identified major market crashes: **1997, 2008-09, and 2020**.

### **3️⃣ Visualizing & Comparing Different Crash Periods**
- Created **detailed visualizations** for each crash period:
  - **Closing prices** before, during, and after the crash.
  - **Daily returns** with volatility spikes.
  - **Drawdown charts** highlighting severe declines.

### **4️⃣ Developing an Early Warning System (EWS)**
- Calculated **10-day rolling average return** and **rolling volatility**.
- Defined warning conditions:
  - **Returns fall below -0.5%**.
  - **Volatility exceeds 2%**.
- Marked **early warning signals** on **synthetic 2025 Sensex data**.

---

## 🔍 Results & Insights
✅ **Crashes show clear pre-crash warning patterns.**  
✅ **Increased volatility and falling returns signal potential crashes.**  
✅ **EWS can help investors act before severe losses occur.**  
✅ **Historical crashes took years to recover, emphasizing risk management.**  

---

## 📊 Visualization Samples
- **Historical Crash Periods** (1997, 2008-09, 2020).
- **Drawdown Analysis Over Time**.
- **Early Warning Signals on Synthetic 2025 Data**.

---

## 🔧 Installation & Usage
### **Requirements**
- Python 3.8+
- Required libraries:
  ```sh
  pip install pandas numpy plotly
  ```
### **Running the Analysis**
1. Clone the repository:
   ```sh
   git clone https://github.com/knight22-21/Stock-Market-Crash-Analysis.git
   cd market-crash-analysis
   ```
2. Run the script:
   ```sh
   python analysis.py
   ```

---

## 📈 Future Improvements
🔹 **Fine-tune warning thresholds using real-world data.**  
🔹 **Incorporate sentiment analysis from news & social media.**  
🔹 **Automate alerts using real-time market data feeds.**  
🔹 **Expand analysis to other indices (NIFTY, S&P 500, Nasdaq).**  

---

🚀 **Stay ahead of market crashes with data-driven insights!** 📊📉

