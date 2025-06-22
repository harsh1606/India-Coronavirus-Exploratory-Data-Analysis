
# 🦠 COVID-19 India Tracker

## 📌 Overview
This project scrapes, processes, and visualizes state-wise COVID-19 data from the official Ministry of Health and Family Welfare (MoHFW) website in India. It collects and aggregates daily data including confirmed cases, cured patients, and deaths, and generates multiple insights and visualizations.

## 📂 Features
- Scrapes real-time COVID-19 data from [mohfw.gov.in](https://www.mohfw.gov.in)
- Cleans and formats the dataset with added metrics like death and recovery percentages
- Adds geospatial data (latitude and longitude) for state-level mapping
- Saves data in daily CSV files and merges all historical data into a single dataset
- Performs analysis to:
  - Show states with the highest number of cases
  - Visualize state-wise recovery and death rates
  - Generate time-based trends
  - Present pie chart of nationwide statistics

## 🛠️ Technologies Used
- `Python`
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `BeautifulSoup`, `requests`
- `folium` (for geographic mapping)
- `glob`, `re`, `datetime` (for file and data management)

## 🚀 How to Run
1. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the main script:
   ```bash
   python covid_tracker.py
   ```
3. The data will be saved as a CSV file (named using the current date) in your working directory.

## 📊 Output
- Daily CSV with updated statistics
- Cumulative dataset `complete.csv`
- Visual charts displaying:
  - State-wise death and recovery numbers
  - Death and recovery percentage comparisons
  - Nationwide pie chart of confirmed, recovered, and death counts

## 📈 Sample Insights
- Total Confirmed Cases in India
- Total Deaths and Death Percentage
- Total Cured and Cured Percentage

## 👤 Author
**Harsh Kumar Tyagi**  
📧 [harshtyagi022@gmail.com](mailto:harshtyagi022@gmail.com)

---

*Data Source: [Ministry of Health and Family Welfare - India](https://www.mohfw.gov.in)*
