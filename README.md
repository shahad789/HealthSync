# HealthSync
# 🏥 Athlete Injury Monitoring System (AI-Powered)

## 📌 Overview

This project is an **AI-based injury prediction system** designed to help coaches, trainers, and medical staff **predict the risk of injury** in athletes using real-time performance and biometric data.

It uses a **Random Forest machine learning model** trained on sports performance data (e.g., height, weight, minutes played, speed, touches) to determine if a player is **at high risk** of injury. The system is designed for future integration with **wearable IoT devices** for real-time monitoring.

---

## ⚙️ How It Works

1. **Input:** Data from a player (like height, speed, minutes played).
2. **Preprocessing:** Data is scaled (normalized) to fit the model.
3. **Prediction:** The model checks if the player is likely to be injured.
4. **Output:** You get:
   - 🟢 Injury Prediction (Yes/No)
   - 📊 Probability of Injury (e.g., 85%)
   - ⚠️ Main Risk Factors (e.g., minutes played, weight)

---

## 🧠 Technologies Used

- Python 🐍
- Pandas 📊
- Scikit-learn 🔍
- NumPy 🔢
- Joblib 📦 (for saving/loading model and scaler)

