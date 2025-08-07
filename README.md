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
- Filter for Summer Olympics only  
- Merge athlete data with NOC regions  
- Create dummy variables for medals (Gold, Silver, Bronze)  

### 2. Exploratory Data Analysis (EDA)
- Generate stats: number of editions, host cities, sports, events, athletes, and nations  
- Visualize trends in participation and event counts  

### 3. Medal Tally Analysis
- Interactive tool (via Streamlit) to select year and country  
- Display:
  - Overall medal tally  
  - Year-wise performance  
  - Country-wise performance  

### 4. Country-wise Performance
- Analyze country-specific performance  
- Identify top sports by country  
- List top 10 athletes for selected country  

### 5. Athlete-wise Analysis
- Age distribution of athletes and medalists  
- Sports-wise age distribution  
- Height and weight analysis  
- Male vs female participation trends  

---

## 💻 Interactive Visualizations with Streamlit

### Features:
- User-friendly UI: dropdowns, radio buttons, charts  
- Dynamic tables and plots  
- Instant exploration of Olympic data  

### Setup Instructions:
```bash
pip install streamlit pandas plotly seaborn
streamlit run app.py

📊 Data Visualization Libraries
- Plotly: For interactive line and scatter plots
- Seaborn: For statistical visualizations like heatmaps
