# 📊 PhonePe Pulse Data Visualization & 2026 AI Forecast

## 🚀 Project Overview
This project is a comprehensive data science solution for analyzing and forecasting digital payment trends in India using the **PhonePe Pulse** dataset. It combines a robust data pipeline, interactive visualizations, and a high-accuracy machine learning engine to provide actionable business insights.

### 🎯 Key Objectives:
- **Data Engineering:** Extract and clean 2018-2024 transaction and user data.
- **Interactive Analytics:** Build a live dashboard to explore regional performance.
- **AI Forecasting:** Predict transaction volumes for Q1 2026 using an optimized Random Forest model.

---

## 🛠️ Tech Stack
| Category | Tools & Libraries |
| :--- | :--- |
| **Language** | Python 3.x |
| **Data Handling** | Pandas, Numpy, JSON |
| **Database** | SQLite3 |
| **Machine Learning** | Scikit-Learn (Random Forest Regressor), Joblib |
| **Visualization** | Plotly Express, Streamlit |

---

## 📈 Performance & Results
- **Machine Learning Accuracy:** Achieved an **R-squared score of 0.9959** using a Tuned Random Forest model.
- **2026 Forecast (Maharashtra):** The model predicts a baseline amount of **₹20.97B**, representing a steady **22.63% growth** from the 2024 average.
- **Top Growth Drivers:** The analysis identified **Transaction Intensity** and **Average Transaction Value (ATV)** as the most critical predictors of future volume.

---

## 📂 Repository Structure
- `app.py`: The core Streamlit application file.
- `phonepe_pulse.db`: SQLite database containing cleaned and aggregated tables.
- `phonepe_rf_model.pkl`: The serialized (saved) machine learning model for instant forecasting.
- `PhonePe_Pulse_Data_Analysis.ipynb`: The full development notebook covering EDA and Model Training.

---

## 💻 How to Run Locally

1. **Clone the repository:**
```bash
git clone [https://github.com/hubsukalp/PhonePe-Pulse-Data-Visualization-and-Forecasting.git](https://github.com/hubsukalp/PhonePe-Pulse-Data-Visualization-and-Forecasting.git)
````

2.  **Navigate to the directory:**

<!-- end list -->

```bash
cd PhonePe-Pulse-Data-Visualization-and-Forecasting
```

3.  **Install dependencies:**

<!-- end list -->

```bash
pip install streamlit pandas plotly joblib
```

4.  **Launch the Dashboard:**

<!-- end list -->

```bash
streamlit run app.py
```

