# 🌦️ Weather Data Analysis System

## 📌 Project Description
The Weather Data Analysis System is a Python-based web application developed using Flask and MySQL. It helps users upload historical weather datasets in CSV format, validate weather information, store records in a database, and analyze weather conditions through statistical calculations and interactive charts.

The system uses Pandas, NumPy, and Matplotlib to analyze weather data and display meaningful insights.

**Note:** This project analyzes historical weather data. It does not predict future weather.

## 🚀 Technologies Used
- Python
- Flask
- MySQL
- HTML
- CSS
- JavaScript
- Pandas
- NumPy
- Matplotlib

## ✨ Features
- Upload weather datasets using CSV files.
- Validate uploaded weather records.
- Store weather information in MySQL database.
- Calculate average, minimum, and maximum temperatures.
- Analyze humidity and rainfall.
- Generate graphical weather reports.
- View stored weather records.
- Delete individual records or all records.

## 📊 Data Analysis
The application provides:
- Daily Temperature Trends
- Monthly Rainfall Analysis
- Monthly Average Humidity
- Temperature vs Rainfall Comparison

## 📁 Project Structure
```text
Weather_Data_Analysis_System/
│
├── app.py
├── requirements.txt
├── README.md
├── sample_weather.csv
├── .env.example
│
├── analysis/
│   └── weather_analysis.py
│
├── database/
│   ├── schema.sql
│   └── upgrade_duplicate_protection.sql
│
├── templates/
│   ├── index.html
│   ├── base.html
│   ├── analysis.html
│   ├── upload.html
│   └── records.html
│
├── static/
│   └── css/
│       └── style.css
│
├── tests/
│   └── test_analysis.py
│
└── uploads/
```

## ⚙️ Installation and Setup

1. Install Python 3.10 or above.
2. Install MySQL Server.
3. Install the required packages:

```bash
pip install -r requirements.txt
```

4. Configure MySQL database credentials using the `.env` file.
5. Execute `database/schema.sql` in MySQL.
6. Run the application:

```bash
python app.py
```

7. Open your browser and visit:

```text
http://127.0.0.1:5000
```

## 🧪 Testing

Run the following command:

```bash
pytest -q
```

## 🎯 Project Objective
The main objective of this project is to analyze historical weather information, identify weather patterns, perform statistical calculations, and present the results through graphical visualizations.

## 🔮 Future Enhancements
- Add weather forecasting functionality.
- Implement user authentication.
- Support more weather datasets.
- Improve dashboard visualizations.
- Add advanced statistical analysis.

## 👩‍💻 Conclusion
The Weather Data Analysis System provides an efficient way to upload, manage, analyze, and visualize historical weather information. It demonstrates the practical application of Python programming, database management, web development, and data visualization.

**Project Type:** Python Web Application  
**Domain:** Data Analysis  
**Database:** MySQL
