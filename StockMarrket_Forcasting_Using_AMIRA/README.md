# 📈 Stock Price Forecasting (Tesla - TSLA)

This project demonstrates **time series forecasting** of Tesla stock prices using **ARIMA and SARIMA models**.  
The workflow covers data preprocessing, model selection, evaluation, and visualization of predictions.  

---

## 🚀 Project Overview
- Load Tesla stock dataset (`TSLA.csv`)
- Preprocess data (remove unused columns, set Date as index)
- Train/Test split (80/20)
- Apply **ARIMA** and **SARIMA** models
- Evaluate performance using **RMSE, MAE, MAPE**
- Implement **rolling forecast** for higher accuracy
- Interactive function to **predict next close price**

---

## 📂 Repository Structure
```
├── stock_forecasting.ipynb   # Jupyter/Colab notebook with full code
├── TSLA.csv                  # Dataset (Tesla stock prices)
└── README.md                 # Project documentation
```

---

## 🛠️ Requirements
Install dependencies before running the notebook:

```bash
pip install numpy==1.26.4
pip install pmdarima
pip install statsmodels
pip install scikit-learn
pip install matplotlib seaborn pandas
```

---

## ▶️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/NoorFatimaAnwar/Time_Series_Model_Projects.git
   cd Stock-Forecasting
   ```

2. Open the notebook in **Google Colab** or **Jupyter Notebook**:
   ```bash
   jupyter notebook stock_forecasting.ipynb
   ```

3. Upload the dataset (`TSLA.csv`) when prompted (if not already in the folder).

4. Run all cells to train the models and view results.

---

## 📊 Results & Evaluation
The notebook compares **ARIMA** and **SARIMA** models.  

Evaluation metrics:
- **RMSE** (Root Mean Squared Error)  
- **MAE** (Mean Absolute Error)  
- **MAPE** (Mean Absolute Percentage Error)  

📌 Example visualization of forecasts:
- Train vs Test split  
- Forecasted vs Actual closing prices  
- Rolling Forecast for 1-step ahead prediction  

---

## 🔮 Future Work
- Experiment with **Prophet** (Facebook/Meta) for stock forecasting  
- Use external features (technical indicators, macroeconomic factors)  
- Deploy model as a **Flask API** or **Streamlit App**  

---
## 📌 Disclaimer
This Project is for **educational Purpose only**.
Stock price forcasting is highly uncertain and should **not** be used for finnacial decision.

---
## ✨ Author
👩‍💻 Developed by **Noor Fatima**  

