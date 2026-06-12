# 🎵 Top Song Durations Analysis

> Academic project developed during the **Data Science Essentials with Python** course from the Cisco Networking Academy.

## 📖 Overview

This project analyzes the duration of annual top-hit songs over more than a century of music history.

Using a dataset containing the most popular songs from different years, the study explores how song lengths have evolved over time, identifying trends, outliers, and changes in listener preferences and music industry standards.

The project applies data cleaning, feature engineering, exploratory data analysis, and visualization techniques using Python.

---

## 🎯 Objectives

* Analyze the duration of top-charting songs across different years.
* Convert song duration into a numerical format suitable for analysis.
* Identify the shortest and longest songs in the dataset.
* Visualize duration trends over time.
* Explore how song lengths have changed throughout music history.

---

## 📊 Dataset

### Top Song Durations Dataset

The dataset contains annual top-hit songs and their durations.

### Attributes

| Column   | Description                            |
| -------- | -------------------------------------- |
| year     | Year the song reached the top position |
| artist   | Artist or group                        |
| title    | Song title                             |
| duration | Song duration in HH:MM:SS format       |

### Dataset Size

* 101 records
* 4 original attributes

---

## 🔬 Analyses Performed

### Data Exploration

The first stage involves loading and inspecting the dataset using Pandas.

Key tasks include:

* Dataset inspection
* Data type verification
* Identification of minimum and maximum durations

---

### Duration Conversion

Since duration is stored as text, the project converts it into numerical values.

#### Steps

1. Split duration into hours, minutes, and seconds.
2. Convert values to integers.
3. Calculate total duration in seconds.

Formula used:

```python
total_seconds = h * 3600 + m * 60 + s
```

This transformation enables quantitative analysis and visualization.

---

### Shortest Song Analysis

The project identifies the shortest song in the dataset by comparing duration values.

This allows the detection of unusual or exceptionally brief chart-topping songs.

---

### Longest Song Analysis

Similarly, the longest song in the dataset is identified after converting durations into seconds.

This helps reveal outliers and historical exceptions in song length.

---

## 📈 Visualizations

### Song Duration Over Time

A line chart is generated to visualize duration trends throughout the years.

The graph shows:

* Variations in song length over time;
* Historical peaks and declines;
* Long-term trends in music duration.

### Duration in Seconds

To improve accuracy, a second visualization uses total duration in seconds rather than text-based time values.

This allows a more precise comparison between songs from different decades.

---

## 🔍 Key Insights

The analysis reveals several interesting patterns:

* Song durations vary significantly across decades.
* Some periods contain noticeably longer chart-topping songs.
* Modern hit songs tend to follow different duration patterns than older recordings.
* Converting durations to seconds enables more meaningful trend analysis and comparisons.

---

## 📊 Data Science Techniques Applied

* Data Loading
* Data Cleaning
* Data Type Conversion
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Data Visualization
* Time-Based Trend Analysis

---

## 🛠 Technologies Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

---

## 🚀 How to Run

### Install Dependencies

```bash
pip install pandas matplotlib
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Open the Project

```text
top-songs-project.ipynb
```

Execute all notebook cells to reproduce the analyses and visualizations.

---

## 📚 Concepts Covered

* Python for Data Analysis
* Data Wrangling
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Data Visualization
* Trend Analysis
* Working with Time-Based Data

---

## 🎓 Academic Context

This project was developed as part of the **Data Science Essentials with Python** course offered by the Cisco Networking Academy.

The project demonstrates how Python can be used to transform raw data into meaningful insights through cleaning, analysis, and visualization techniques.

---

## 📜 Course Information

**Course:** Data Science Essentials with Python

**Institution:** Cisco Networking Academy

### Topics Covered

* Python Programming
* Data Analysis with Pandas
* Data Visualization
* Exploratory Data Analysis
* Working with Real-World Datasets
* Statistical Reasoning

---

## 👨‍💻 Author

**Tamyres Silva**

Academic project developed as part of the Cisco Networking Academy's Data Science Essentials with Python program.
