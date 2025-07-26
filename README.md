# intern-task1-health-edtech-dashboard

# 💡 Day 1 – Health & Education Dashboard (AIML Internship Task)

This is **Task 1** . The goal was to simulate dashboards for **Health Monitoring** and **Student Performance Tracking** using dummy datasets and Streamlit.

---

## 📅 Task Summary

> **Day 1 (6–8 hrs): System Setup + Dashboard Creation**

- ✅ Created two dummy datasets:
  - `patient_health.csv` – Simulated heart rate, blood pressure, oxygen levels
  - `student_scores.csv` – Simulated student scores by date
- ✅ Built a live dashboard using **Streamlit**
- ✅ Visualized key metrics over time
- ✅ Implemented basic **alert logic** for low oxygen, high heart rate, and low scores

---

## 📊 Features

### 💓 Health Monitoring
- Line chart of:
  - Heart Rate
  - Blood Pressure
  - Oxygen Levels
- Alerts:
  - ⚠️ Low oxygen if value < 94
  - 🚨 High heart rate if value > 100

### 📚 Education Monitoring
- Line chart of student scores over time
- Alerts:
  - 🔴 Low scores if value < 50

---

## 🛠️ Tech Stack

- Language: **Python 3.9+**
- Dashboard: **Streamlit**
- Data: **Pandas, CSV files**
- Visuals: Streamlit's native line charts

---

## 🚀 How to Run the Dashboard

1. Clone this repository or download the code.
2. Install the required packages:
   ```bash
   pip install streamlit pandas matplotlib

