#  Electric Vehicle (EV) Sales Analysis & Prediction – India

##  Overview
This project analyzes and predicts **Electric Vehicle (EV) sales across Indian states** using data analytics and machine learning.  
We explore sales trends over time, compare adoption rates between states, and identify the factors driving EV adoption.  

The project also includes **predictive modeling** to estimate future EV sales based on historical data.



## 📊 Dataset
- **Source**: Clean Mobility Shift (scraped & preprocessed)
- **Format**: CSV  
- **Rows**: 96,845  
- **Columns**: Year, Month, Date, State, Vehicle Class, Vehicle Category, Vehicle Type, EV Sales Quantity



## 🛠 Tools & Technologies
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **ML Model**: Random Forest Regressor
- **Other Skills**: Data Preprocessing, Feature Engineering, EDA, Predictive Modeling



## 📈 Exploratory Data Analysis (EDA) – Key Graphs

### 1️⃣ EV Sales by State Over the Years
![EV Sales by State Over the Years](EV%20Sales%20by%20State%20over%20the%20years.png)  
*Shows how EV sales have evolved year-by-year for each state. We can clearly see certain states leading the market.*



### 2️⃣ EV Sales by Vehicle Category
![EV Sales by Vehicle Category](EV%20sales%20by%20vehical%20category.png)  
*Compares total EV sales across categories like Passenger and Commercial. Passenger vehicles dominate the EV segment.*



### 3️⃣ Top 10 States by Total EV Sales
![Top 10 States by Total EV Sales](Top%2010%20state%20by%20total%20EV%20Sales.png)  
*Ranks states by total EV sales. Leaders include Maharashtra, Karnataka, and Tamil Nadu.*



### 4️⃣ Monthly EV Sales Trend Heatmap
![Monthly EV Sales Trend Heatmap](Monthly%20EV%20Sales%20Treand%20Heatmap.png)  
*Reveals seasonal sales patterns, with certain months consistently showing higher adoption.*



### 5️⃣ Distribution of EV Sales by Vehicle Type
![Distribution of EV Sales by Vehicle Type](Distrubution%20of%20EV%20Sales%20by%20vehical%20Type.png)  
*Highlights the share of sales between 2-wheelers, 4-wheelers, and other types. Two-wheelers dominate India's EV market.*



### 6️⃣ Yearly EV Sales Growth in India
![Yearly EV Sales Growth in India](Yearly%20Ev%20Sales%20Growth%20in%20india.png)  
*Shows overall growth in EV sales nationwide, with a steep upward trend in recent years.*



##  Machine Learning Model
- **Model Used**: Random Forest Regressor
- **Target Variable**: EV Sales Quantity
- **Performance Metric**: RMSE  
- **Result**: RMSE ≈ **130.58** → On average, predictions differ by about 131 EV units.



##  Key Insights
- EV adoption in India is **growing rapidly**, especially in recent years.
- Certain states lead adoption due to better infrastructure and policies.
- Passenger EVs (especially 2-wheelers) dominate the market.
- There are **seasonal spikes** in sales.
- Features like **State**, **Vehicle Category**, and **Year** are most important for predictions.



##  Business Recommendations
- **Policy Makers**: Focus on improving EV infrastructure in low-adoption states.
- **Manufacturers**: Target high-performing states and plan production to match seasonal peaks.
- **Investors**: EV market shows strong growth potential; consider long-term investment.



## 🚀 How to Run the Project
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
