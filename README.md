# 📊 Real-Time Cryptocurrency Market Sentiment & Price Prediction

![Crypto Dashboard]()

## ✨ Overview
This project predicts cryptocurrency prices by analyzing **real-time Twitter sentiment** and **historical price data**. Using **Natural Language Processing (NLP)** and **Machine Learning (XGBoost, LSTM)**, the system identifies market trends and provides insights via an **interactive Streamlit dashboard**.

## 🛠️ Features
- 🌐 **Real-time Twitter Sentiment Analysis** using VADER & TextBlob
- 📊 **Crypto Price Prediction** using XGBoost & LSTM models
- 🔄 **Live Data Streaming** with WebSockets
- 📈 **Interactive Visualization** via a Streamlit Dashboard
- 🌐 **Deployed on Render & Streamlit Cloud** for global access

## 🌐 Live Demo
- **Dashboard:** [Crypto Prediction Dashboard]()
- **API:** [Crypto Prediction API]()

## 👩‍💻 Tech Stack
- **Programming:** Python, Flask, Streamlit
- **Machine Learning:** XGBoost, LSTM, Sklearn
- **NLP:** VADER, TextBlob, Tweepy
- **Visualization:** Matplotlib, Plotly
- **Deployment:** Render, Streamlit Cloud

## 📘 How It Works
1. **Data Collection:** Fetches real-time crypto prices (Binance API) & Twitter sentiment (Tweepy).
2. **Preprocessing:** Cleans & transforms text data for sentiment scoring.
3. **Feature Engineering:** Computes **SMA, RSI, Sentiment Index**.
4. **Model Training:** Uses **XGBoost & LSTM** for price prediction.
5. **Deployment:** Flask API serves predictions, Streamlit dashboard visualizes data.

## ⚙️ Installation & Setup
### 1. Clone the Repository
```bash
git clone https://github.com/yourgithub/crypto-prediction.git
cd crypto-prediction
```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the Flask API
```bash
python app.py
```
### 4. Run the Streamlit Dashboard
```bash
streamlit run dashboard.py
```

## ✨ Future Improvements
- 💡 **Integrate More Social Media Sources** (Reddit, Telegram, Discord)
- 🎨 **Enhance LSTM Model** with Transformers (GPT-based forecasting)
- ⌛ **Improve Real-Time Streaming** with Kafka or RabbitMQ

---
🌟 **If you like this project, give it a star!** 🌟

