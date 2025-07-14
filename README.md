# 🏏 IPL Data Analysis with PySpark

### 📊 Project Overview

This project explores and analyzes detailed IPL (Indian Premier League) cricket match data using **PySpark**. It processes large-scale, ball-by-ball datasets and extracts key insights about team performance, player impact, toss outcomes, and bowling economy across different seasons.

Designed for scalability and performance, this project uses Spark’s distributed processing power to efficiently handle and analyze structured data.

---

### 🛠️ Technologies Used

* **Apache Spark (PySpark)**
* **Google Colab / Databricks**
* **Pandas** and **Seaborn** for visualization
* **Matplotlib** for plotting
* **CSV** as data source

---

### 📁 Datasets Used

The project uses the following IPL CSV datasets:

| File               | Description                                |
| ------------------ | ------------------------------------------ |
| `Ball_By_Ball.csv` | Ball-wise match data                       |
| `Match.csv`        | Match metadata including results and venue |
| `Player.csv`       | Player information                         |
| `Player_Match.csv` | Player performance per match               |
| `Team.csv`         | Team metadata                              |

---

### 📌 Key Features

#### 🔍 Exploratory Data Analysis (EDA)

* Number of matches played per season
* Venue-wise match distribution
* Impact of toss on match outcomes
* Winning margin and outcome breakdowns

#### 🧮 Statistical Aggregations

* Economy rate of bowlers per season
* Total and average runs per innings
* High-impact deliveries (runs > 6 or wicket)
* Top run scorers per match or season

#### 📊 Visualizations

* Count plots for toss vs match result
* Bar plots for runs, wickets, and top performers
* Season-wise trends using line and bar charts

---

### 🚀 How to Run

#### 📍 Option 1: Google Colab

1. Open the notebook in Colab
2. Install PySpark using:

   ```python
   !pip install pyspark
   ```
3. Upload your datasets to the Colab session
4. Run all cells to reproduce the analysis

---

### 📂 Project Structure

```
ipl-data-analysis/
├── ipl_data_analysis_spark.ipynb  # Main notebook
├── data/
│   ├── Ball_By_Ball.csv
│   ├── Match.csv
│   ├── Player.csv
│   ├── Player_Match.csv
│   └── Team.csv
└── README.md                      # This file
```

---

### 🧠 Skills Demonstrated

* Data Cleaning & Preprocessing with PySpark
* Complex GroupBy and Window Functions
* DataFrame joins and schema definition
* Exploratory Data Analysis (EDA)
* Data Visualization with Seaborn/Matplotlib
* Working in distributed environments (Colab / Databricks)

---
