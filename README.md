# COVID-19 Data Analysis Project

## Project Overview

This project is a comprehensive data analysis of the *Our World in Data COVID-19 dataset. It was carried out as part of an academic assignment by Faith Sawe, with Brian Richard contributing to assist in completing the assignment.

Using the OWID COVID dataset, the project explores key trends and patterns surrounding the COVID-19 pandemic across various countries and continents. The project provides detailed data preprocessing, exploratory data analysis (EDA), visualizations, and insights derived from the dataset.

---

## 👩‍💻 Project Contributors

- *Faith Sawe* – Project owner and primary analyst  
- *Brian Richard* – Contributor (assisted in completing the assignment)

---

## 📂 Dataset

- *Source*: [Owid-Covid-Data Dataset](https://github.com/owid/covid-19-data)
- *Format*: CSV  
- *Description*: Contains worldwide COVID-19 statistics including total cases, deaths, vaccination progress, testing, hospitalizations, and demographic metadata.

---

## 🔧 Tools & Libraries Used

- Python 3  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn

---

## 📊 Key Steps & Analysis

### 1. Data Loading and Cleaning
- Loaded the OWID COVID dataset.
- Dropped unnecessary columns for better clarity and performance.
- Removed rows with missing values in crucial columns like continent.
- Filtered out aggregate entities (like "World") to focus on individual countries.

### 2. Exploratory Data Analysis (EDA)
- Compared total cases and deaths across continents.
- Identified the continent with the highest death-to-case ratio.
- Tracked monthly COVID-19 case trends using date transformations.
- Analyzed continent-wise death counts.

### 3. Insights & Visualizations
- *Total Cases vs Total Deaths*: Identified regions with higher fatality ratios.
- *Top 10 Countries by Deaths*: Highlighted the most affected countries.
- *Monthly Trend of Cases*: Clear visualization of COVID-19 waves over time.
- *Death Count by Continent*: Africa and Europe showed significant variance in death tolls.

### 4. Grouping and Aggregation
- Used grouping operations to:
  - Aggregate case/death statistics by continent and month.
  - Calculate the mean values for numerical features.

---

## 📈 Key Insights

- *Europe* recorded the highest number of total deaths.
- *Africa* had a lower total death count but still showed notable fatality in certain countries.
- The *death-to-case ratio* varied significantly across continents, indicating possible differences in healthcare infrastructure and pandemic response.
- Monthly trends revealed periodic spikes, aligning with major global COVID-19 waves.
- The *top 10 countries by total deaths* included both developed and developing nations, showing the pandemic’s global reach.

---

## 📌 Project Purpose

The goal of this project was to:
- Apply data science and analysis techniques using Python.
- Extract actionable insights from real-world pandemic data.
- Practice data cleaning, transformation, and visualization.
- Demonstrate competency in data storytelling using charts and statistical summaries.

---

## 📁 Repository Structure

```bash
.
├── python-project.ipynb       # Main analysis notebook
├── README.md                  # Project overview and documentation
└── owid-covid-data.csv        # Dataset (external, linked from OWID)
