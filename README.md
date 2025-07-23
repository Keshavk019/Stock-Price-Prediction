# 📈 Stock Price Prediction using LSTM and Streamlit

A web-based application that predicts future stock prices using an LSTM (Long Short-Term Memory) deep learning model, with interactive visualizations powered by Streamlit.

---

<img width="614" height="425" alt="image" src="https://github.com/user-attachments/assets/5a55f3aa-b1b5-44b2-a14f-dc49eeabdb78" />


---

## 🧠 Project Overview

This project focuses on predicting stock prices using a Recurrent Neural Network (RNN) architecture — specifically, an LSTM model, which is well-suited for time series forecasting.

The application allows users to:

- Enter a **stock ticker symbol** (e.g., `AAPL`, `GOOGL`)
- View historical stock trends
- See visualizations with **moving averages**
- View model-predicted vs actual prices

---

## ⚙️ Technique Used

###  Long Short-Term Memory (LSTM)

- LSTM is a type of **Recurrent Neural Network (RNN)** capable of learning long-term dependencies.
- It is highly effective for **sequential/time-series data**, such as stock prices.
- Our model takes in the **past 100 days of closing prices** and learns to predict the next prices.

###  Rolling Averages

- **MA100 & MA200** (100-day and 200-day moving averages) are used to visualize long-term trends.
- Help users understand momentum and support/resistance zones.

---

##  Model Architecture
- Input -> LSTMS -> Dense ->  Output

## Results

<img width="492" height="587" alt="image" src="https://github.com/user-attachments/assets/4a635a0f-e24c-4b13-971c-de8fce04b17e" />

<img width="515" height="600" alt="image" src="https://github.com/user-attachments/assets/342df6e8-08b2-4b1a-8f8f-b73ddef08971" />





