# 🦠 COVID-19 Trend Analysis and Forecasting with Python

## 📌 Project Overview

This project explores global and India-specific COVID-19 trends through data analysis, exploratory data analysis (EDA), interactive visualization, and time-series forecasting.

Using historical COVID-19 data, the project analyzes confirmed cases, recoveries, and deaths to understand how the pandemic evolved over time.

It also applies **Facebook Prophet** to historical confirmed-case data to generate seven-day forecasts for global and India-specific trends.

## 🎯 Project Objectives

- Analyze the impact of COVID-19 globally and in India.
- Explore trends in confirmed, recovered, and death cases.
- Examine daily and cumulative case patterns.
- Analyze infection and recovery rate trends.
- Create interactive visualizations to identify patterns and trends.
- Apply time-series forecasting to predict confirmed cases over the following seven days.

## 🛠️ Technologies & Libraries

| Technology | Purpose |
|:---|:---|
| **Python** | Programming language |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical operations |
| **Plotly** | Interactive data visualization |
| **Facebook Prophet** | Time-series forecasting |
| **Jupyter Notebook** | Development environment |

## 🔍 Project Workflow

### 1. Data Collection & Preprocessing

- Load historical COVID-19 datasets from CSV and Excel files.
- Combine and organize datasets using Pandas.
- Clean and prepare data for analysis.

### 2. Exploratory Data Analysis (EDA)

- Explore global COVID-19 statistics.
- Analyze India's COVID-19 trends.
- Examine confirmed, recovered, and death cases.
- Identify patterns in daily and cumulative case counts.

### 3. Data Visualization

- Visualize global cumulative confirmed cases.
- Analyze daily new confirmed cases.
- Explore recovery and death trends.
- Compare global and India-specific trends.
- Create interactive visualizations using Plotly.

### 4. Time-Series Forecasting

- Apply Facebook Prophet to historical confirmed-case data.
- Develop forecasting models for global cases and India.
- Generate seven-day forecasts.
- Visualize historical trends alongside predicted values.

## 📊 Key Analysis & Visualizations

The project includes visualizations covering:

- Global cumulative COVID-19 trends.
- Daily confirmed cases.
- Global recovery and death patterns.
- India-specific COVID-19 trends.
- Historical confirmed cases and seven-day forecasts.

Selected visualizations are available in the `images/` folder.

## 📁 Repository Structure

```text
COVID-19-Trend-Analysis-and-Forecasting/
|
├── images/
│   ├── global_cumulative_trends.png
|   ├── global_daily_cases
|   ├── global_infection_recovery_rates
|   ├── global_prophet_forecast_plotly
|   ├── india_cumulative_trends
|   ├── india_daily_cases
|   ├── india_infection_recovery_rates
│   └── india_prophet_forecast_plotly
│
├── COVID-19 Analysis and Forecasting.ipynb
├── README.md
└── covid_19_clean_complete.csv
```

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook

### Installation

Install the required libraries:

```bash
pip install pandas numpy plotly prophet jupyter
```

### Running the Project

1. Clone or download this repository.
2. Ensure the dataset and Jupyter Notebook are in the same directory.
3. Install the required dependencies.
4. Open the notebook using Jupyter Notebook.
5. Run the cells sequentially to reproduce the analysis and forecasting.

## 📈 Forecasting Approach

**Facebook Prophet** is used to model historical confirmed-case trends and generate predictions for the following seven days.

Separate forecasting models are developed for global COVID-19 data and India-specific data.

The predicted trends are visualized alongside historical observations to explore the potential future progression of confirmed cases.

**Note:** The project focuses on time-series forecasting and visualization. Forecast accuracy was not evaluated using statistical error metrics.

## 🎓 Project Background

- **Project Type:** Academic Capstone Project
- **Program:** Executive PG Certification in Data Science & AI
- **Institution:** Intellipaat

---

*This project demonstrates the practical application of Python, data preprocessing, exploratory data analysis, interactive visualization, and time-series forecasting to a real-world public health dataset.*
