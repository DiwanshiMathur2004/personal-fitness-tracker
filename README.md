# 🏃‍♀️ AI-Powered Fitness Calorie Prediction System

This project predicts how many **kilocalories** a user burns during physical activity based on key health and exercise parameters. It also provides **general insights** and finds **similar user profiles** using a machine learning model trained on fitness data.

---

## 💡 Features

- 🔥 Predicts calories burned from user inputs
- 📊 Compares your health stats with dataset trends
- 🔁 Recommends similar profiles using unsupervised learning
- ⚙️ Built with Python and machine learning libraries

---

## 📥 User Input

| Parameter             | Example | Description                              |
|-----------------------|---------|------------------------------------------|
| Age                   | 21      | Age in years                              |
| BMI                   | 23.88   | Body Mass Index                           |
| Duration              | 30      | Exercise time in minutes                  |
| Heart Rate            | 120     | Beats per minute during activity          |
| Body Temperature (°C) | 37.0    | Body temperature during activity          |
| Gender                | female  | Gender of the user                        |

---

## ✅ Output

### 🔥 Kilocalories Burned

178.55 kilocalories
---

### 📊 General Information

You are older than 3.0% of other people.

Your exercise duration is higher than 100.0% of other people.

You have a higher heart rate than 100.0% of other people during exercise.

You have a higher body temperature than 0.0% of other people during exercise.

---

### 🔁 Similar Results

Examples:

Age: 22, BMI: 24.1, Duration: 30, HR: 118 → 176.5 kcal

Age: 20, BMI: 23.5, Duration: 29, HR: 122 → 179.2 kcal

---

## 🖼️ Screenshots

### 🔹 Input Form

![Input Screenshot](images/Screenshot (325).png)

---

### 🔹 Output Display 1

![Output Screenshot 1](images/Screenshot (326).png)

---
### 🔹 Output Display 2

![Output Screenshot 2](images/Screenshot (327).png)

---

## 🚀 How to Run the App

1. Clone the repository
2. Install required packages:
pip install -r requirements.txt
3. Run the app (e.g., Streamlit):
4. streamlit run app.py
