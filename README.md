# 🏅 Olympics Data Analysis with Machine Learning

The Olympic Games have a rich history and are one of the most celebrated sporting events globally. With data spanning over a century, this project leverages machine learning and data analysis techniques to uncover patterns, trends, and insights that enhance our understanding of the Games — and even help predict future outcomes.

---

## 🎯 Objectives

- **Data Preprocessing:** Clean and prepare the dataset for analysis.
- **Exploratory Data Analysis (EDA):** Visualize and summarize the data to uncover underlying patterns.
- **Medal Tally Analysis:** Analyze medal counts by year and country.
- **Country-wise Analysis:** Investigate the performance of specific countries over time.
- **Athlete-wise Analysis:** Explore data on individual athletes, including age distributions and performance trends.

---

## 📂 Datasets Used

- **Athlete Events Dataset:** Information on athletes, their events, and results from past Olympic Games.
- **NOC Regions Dataset:** Maps National Olympic Committees (NOCs) to their respective countries/regions.

---

## 🧠 Methodology

### 1. Data Preprocessing
- Load datasets
- Filter for Summer Olympics data only
- Merge athlete data with NOC regions
- Create dummy variables for medals (Gold, Silver, Bronze)

### 2. Exploratory Data Analysis (EDA)
- Generate statistics: Number of editions, host cities, sports, events, athletes, and nations
- Visualize time-based trends in participation and event counts

### 3. Medal Tally Analysis
- Build an interactive tool (via Streamlit) to select year and country
- Display:
  - Overall medal tally
  - Year-wise performance
  - Country-wise performance

### 4. Country-wise Performance Analysis
- Analyze country-specific performance over the years
- Identify top sports for a given country
- List the top 10 athletes from that country

### 5. Athlete-wise Analysis
- Analyze age distribution of athletes and medalists
- Compare sports-wise age distribution
- Visualize height and weight trends
- Examine male vs female participation over time

---

## 💻 Interactive Visualizations with Streamlit

### Features:
- Easy-to-use interface with dropdowns, radio buttons, and charts
- Dynamic tables and plots
- Instant exploration of Olympic data

### Setup Instructions:
```bash
pip install streamlit pandas plotly seaborn
streamlit run app.py
```

---

## 📊 Data Visualization Libraries

- **Plotly:** For interactive and beautiful line plots and scatter plots
- **Seaborn:** For statistical visualizations like heatmaps

### Sample Visualizations:
- Line plots (e.g., number of nations, athletes over time)
- Heatmaps (country vs sport performance)
- Scatter plots (height vs weight)

---

## 🔮 Future Directions

- **Predictive Modeling:** Forecasting medal counts, athlete performance, etc.
- **Advanced Analytics:** Time-series analysis, clustering, anomaly detection
- **Real-time Analysis:** Dashboard integration during live Olympic events

---

## 📁 Project Structure

```
olympics-analysis/
│
├── data/
│   ├── athlete_events.csv
│   └── noc_regions.csv
│
├── preprocessor.py
├── helper.py           
├── app.py     # Streamlit App
└── README.md
```

---

## 🙌 Acknowledgements

This project uses open datasets from [Kaggle Olympic History Data](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results) and is inspired by various public analysis and visualization notebooks.
