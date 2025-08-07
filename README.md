# 🌫️ Air Quality Forecast Dashboard

An interactive and visually engaging dashboard built with Streamlit and Plotly to forecast air quality using CO concentration data. This project utilizes Facebook's Prophet model for forecasting and stores results in MongoDB.

---

## 🚀 Features

- 📊 **Visualize Historical CO Concentration** with interactive line charts.
- 🔮 **Forecast Future CO Levels** for 3 to 14 days using Prophet.
- 💾 **Save Forecasts to MongoDB** automatically.
- 📈 **Display Confidence Intervals** with upper and lower bounds.
- 🖼️ **Clean and Colorful UI** using Streamlit + Plotly.

---

## 🛠️ Technologies Used

| Purpose           | Technology / Library       |
|-------------------|----------------------------|
| Dashboard         | Streamlit                  |
| Visualization     | Plotly                     |
| Forecasting       | Prophet                    |
| Data Handling     | Pandas                     |
| Database          | MongoDB via PyMongo        |
| Version Control   | Git + GitHub               |

---

## 📦 Requirements

Install all Python packages using:

pip install -r requirements.txt

Packages include:

- streamlit
- plotly
- pandas
- prophet
- pymongo

---

## 📂 Project Structure

```
air-quality-forecast/
│
├── g.py                # Main Streamlit dashboard
├── prepare_data.py     # Preprocessing for historical data
├── forecast_model.py   # Prophet model code
├── mongo_utils.py      # MongoDB utility functions
├── requirements.txt    # Required packages
├── README.md           # Project documentation
├── data/               # (Optional) Folder for CSV files
```

---

## ▶️ How to Run the Project

1. **Clone the repository**:

git clone https://github.com/AkulaArchana04/air-quality-forecast.git
cd air-quality-forecast


2. **Install dependencies**:


pip install -r requirements.txt


3. **Start the app**:


streamlit run g.py


4. **Open in browser**:

Visit `http://localhost:8501` to use the dashboard.

---

## 🎯 Use of the Project

This dashboard is designed to:

- Help visualize real-time and historical air quality data.
- Forecast CO levels for early warning and action.
- Store and track forecasts for analysis.
- Assist researchers, environmentalists, and public health officials.

---

## 👩‍💻 Author

**Archana Akula**  
