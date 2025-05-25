# 🌍 Global Temperature Anomaly Analysis

This project analyzes global temperature anomalies over time, focusing on the identification of trends, seasonal patterns, and forecasting future temperature anomalies. The analysis uses historical temperature data from 1880 to 2023 and applies both statistical and machine learning methods (ARIMA and LSTM) to gain insights into global climate change.

---

## 🔑 Key Features

- **📊 Data Segmentation**  
  Data is divided into 10-year segments (1880–2023) to analyze decadal trends and seasonal behavior.

- **📈 Trend Analysis**  
  Moving averages and seasonal decomposition methods help identify long-term warming trends and periodic fluctuations.

- **🧪 Statistical Testing**  
  Applied ADF tests for stationarity and used t-tests/ANOVA to validate the hypothesis of increasing anomalies.

- **📉 ARIMA Modeling**  
  Time series modeled using ARIMA (AutoRegressive Integrated Moving Average). Model selection is automated using `auto.arima()`. Validated with AIC, BIC, and residual diagnostics.

- **🧠 LSTM Forecasting**  
  Implemented LSTM (Long Short-Term Memory) deep learning model to capture non-linear dependencies and provide more accurate long-term predictions.

- **📊 Visualization**  
  Includes ACF/PACF plots, decomposition graphs, trend lines, and forecast charts for clear interpretation.

- **🔮 Forecasting**  
  Short- and long-term forecasts using ARIMA and LSTM. Forecast performance evaluated with MAE, RMSE, and AIC.

---

## 🧰 Tools and Libraries

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Statsmodels (`ARIMA`)
- TensorFlow / Keras (`LSTM`)
- Jupyter Notebook

---

## 📂 Data

Global temperature anomaly data (1880–2023) sourced from:
- [NOAA](https://www.ncdc.noaa.gov/)
- [NASA GISTEMP](https://data.giss.nasa.gov/gistemp/)
- [Berkeley Earth](http://berkeleyearth.org/data/)

Data preprocessing includes:
- Cleaning & handling missing values  
- Formatting for time series modeling  

---

## 📊 Results

- Clear long-term warming trend detected.
- Sharpest rise in anomalies observed in recent decades.
- **LSTM outperformed ARIMA** in long-term forecasts due to its ability to model complex non-linear patterns.

---

## 🚀 Future Work

- Explore **hybrid ARIMA + LSTM models** for enhanced accuracy.
- Incorporate external factors (e.g., solar cycles, CO₂ levels, volcanic activity).
- Deploy **real-time forecasting** using streaming data.

---

## 🤝 Contribution

Contributions are welcome!  
You can:
- Improve model accuracy
- Add new visualizations
- Enhance preprocessing or real-time data integration

Submit issues or pull requests via the [GitHub repository](https://github.com/RatneshDPatil).

---

## 📬 Contact

**Ratnesh Dnyaneshwar Patil**  
📧 [ratneshpatil@outlook.com](mailto:ratneshpatil@outlook.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/ratnesh-patil) | [GitHub](https://github.com/RatneshDPatil)
