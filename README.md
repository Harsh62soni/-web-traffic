# InsightViz: Web Traffic Analyzer 📊

This project is a **data cleaning and visualization dashboard** for analyzing web traffic data using Python. It processes a CSV export of web analytics data, cleans and formats it, and provides insightful visualizations about user behavior across different channel groups and time.

---

## 🚀 Features

- Data cleaning & formatting with Pandas
- Time-based conversion and parsing of date-hour formats
- Multiple data visualizations using **Matplotlib** and **Seaborn**:
  - User and session trends over time
  - Channel-wise user distribution
  - Engagement time per channel
  - Engagement rate analysis (boxplot)
  - Engaged vs Non-Engaged sessions
  - Heatmap of traffic by hour and channel
  - Engagement rate vs sessions over time

---

## 📁 Dataset Used

CSV File: `data-export (1).csv`  
The dataset includes:
- Channel group
- Date and Hour
- Sessions, Users, Events
- Engagement-related metrics

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** - Data manipulation
- **NumPy** - Numerical operations
- **Matplotlib** - Plotting graphs
- **Seaborn** - Statistical data visualization

---

## 📊 Sample Visualizations

- Line chart of sessions and users over time
- Bar plots of users per channel
- Boxplot of engagement rate
- Heatmap of sessions by hour/channel
- Combined plot of engagement rate vs sessions

---

## 📦 How to Run

1. Clone the repo or download the script
2. Make sure Python and required libraries are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn
