#  European Energy Price Forecasting with Deep Learning

##  Project Overview
Imagine having access to a treasure trove of information about European energy markets.  
This project leverages **hourly electricity price data across European power systems** to build deep learning models that can **forecast future energy prices**.

European energy markets are highly dynamic due to:
- Increasing integration of renewable energy
- Continuous supply–demand fluctuations
- Geopolitical and economic influences

By applying **sequence-based deep learning models**, this project aims to uncover hidden temporal patterns and provide accurate, robust forecasts that support **energy procurement, investment planning, and risk management**.

---

##  Aim
The primary aim of this project is to **predict hourly electricity prices in European energy markets** using deep learning time-series models that can capture **nonlinear behavior and long-term temporal dependencies**.

---

##  Objectives
- Model hourly electricity price time series for European markets
- Capture both short-term and long-term temporal dependencies
- Compare advanced deep learning architectures for time-series forecasting
- Evaluate model performance using standard error metrics
- Identify the most reliable architecture for energy price prediction
- Support decision-making in energy trading, procurement, and policy analysis

---

##  Models Used
This project **exclusively focuses on deep learning models** suitable for sequential data:

### 1️⃣  RNN
- Baseline recurrent neural network
- Captures short-term temporal patterns
- Simple and fast to train
- Limited ability to model long-term dependencies

---

### 2️⃣ LSTM (Long Short-Term Memory)
- Designed to overcome vanishing gradient problems
- Learns long-term and seasonal dependencies
- Well-suited for volatile and nonlinear energy prices
- Strong performance on medium- and long-horizon forecasts

---

### 3️⃣ GRU (Gated Recurrent Unit)
- Simplified variant of LSTM
- Faster training with fewer parameters
- Suitable for real-time and near-real-time applications
- Competitive accuracy with lower computational cost

---

### 4️⃣ CNN-LSTM (Hybrid Model)
- CNN layers extract local temporal features
- LSTM layers learn long-term dependencies
- Effective at capturing sudden price spikes and repeating hourly patterns
- Often delivers the highest forecasting accuracy

---

##  Model Comparison Summary

| Model     | Strength                                | Limitation                          |
|----------|------------------------------------------|-------------------------------------|
| RNN      | Simple and fast baseline                  | Weak long-term memory               |
| LSTM     | Strong long-term dependency learning      | Higher training time                |
| GRU      | Faster and lightweight                   | Slightly less expressive than LSTM  |
| CNN-LSTM | Best performance on complex time series   | More complex architecture           |

---

##  Dataset Description
- **Region:** European energy markets
- **Frequency:** Hourly
- **Target Variable:** Electricity price
- **Features may include:**
  - Timestamp
  - Market / system identifier
  - Historical price values
  - Lagged features and rolling statistics

Hourly granularity enables:
- Real-time market analysis
- Detection of short-lived price shocks
- Improved understanding of intraday price behavior

---

##  Methodology
1. Data preprocessing and normalization  
2. Creation of sliding windows for supervised learning  
3. Model training using deep learning architectures  
4. Performance evaluation using:
   - RMSE
   - MAE
   - MAPE  
5. Comparison of predicted vs actual price curves  

---

##  Evaluation Metrics
- **RMSE (Root Mean Squared Error)**  
- **MAE (Mean Absolute Error)**  
- **MAPE (Mean Absolute Percentage Error)**  

These metrics ensure robustness and comparability across models.

---

##  Key Takeaways
- Deep learning models significantly outperform classical approaches for energy price forecasting
- **CNN-LSTM and LSTM** achieve the highest accuracy on complex and volatile markets
- **GRU** offers an excellent balance between speed and accuracy
- The approach is highly suitable for real-world energy trading and planning systems

---

##  Future Extensions
- Integration of exogenous variables (weather, renewable generation, demand)
- Multi-market joint forecasting
- Deployment as an AI agent for real-time market monitoring
- Scenario-based forecasting under economic or geopolitical shocks

---

## 📎 Use Cases
- Energy trading and procurement optimization
- Risk management and price volatility analysis
- Policy and economic trend analysis
- Investment decision support in energy infrastructure

---

##  Contribution
Contributions are welcome!  
Feel free to fork the repository, open issues, or submit pull requests.

