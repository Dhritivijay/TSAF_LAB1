# Monthly CO₂ Concentration — Time Series Analysis

## 📌 Overview

This experiment analyzes **monthly atmospheric CO₂ concentration data from Mauna Loa** using Python and time-series analysis techniques.

The analysis focuses on identifying the **long-term trend, seasonal pattern, and residual variation** in atmospheric CO₂ concentration.

---

## 🎯 Objectives

The experiment aims to:

* Load and explore monthly CO₂ concentration data.
* Visualize the complete CO₂ time series.
* Calculate a **12-month moving average**.
* Compare the original series with the moving average.
* Perform **seasonal decomposition**.
* Analyze the observed, trend, seasonal, and residual components.
* Calculate the average seasonal effect for each month.
* Visualize the average CO₂ concentration by month.

---

## 📊 Dataset

**Dataset:** Mauna Loa Atmospheric CO₂ Concentration — Monthly Mean Data

The dataset contains monthly observations of atmospheric CO₂ concentration along with additional information such as:

* Year
* Month
* Decimal Date
* Average CO₂ concentration
* Deseasonalized CO₂ concentration
* Number of days
* Standard deviation
* Uncertainty

The `average` column represents the monthly mean atmospheric CO₂ concentration in **parts per million (ppm)**.

---

## 🛠️ Technologies Used

* **Python 3**
* **Jupyter Notebook**
* **Pandas** — data manipulation and analysis
* **NumPy** — numerical operations
* **Matplotlib** — data visualization
* **Statsmodels** — time-series decomposition

---

## 🔬 Analysis Performed

### 1. Complete Time-Series Visualization

The complete monthly CO₂ concentration series was plotted to observe its overall behavior.

The series shows a clear **long-term increasing trend** along with regular monthly fluctuations.

### 2. 12-Month Moving Average

A 12-month rolling average was calculated to smooth short-term fluctuations and highlight the long-term movement of atmospheric CO₂ concentration.

### 3. Seasonal Decomposition

The time series was decomposed using:

* **Model:** Additive
* **Period:** 12 months

The decomposition separates the series into:

1. **Observed** — original CO₂ concentration
2. **Trend** — long-term movement
3. **Seasonal** — repeating yearly pattern
4. **Residual** — irregular variation

### 4. Monthly Seasonal Effects

The average seasonal effect was calculated for each month from January to December.

This helps identify how the seasonal component contributes to CO₂ concentration during different months of the year.

### 5. Average CO₂ Concentration by Month

The average CO₂ concentration was calculated separately for each month across the dataset and visualized using a bar chart.

---

## 📈 Key Observations

* Atmospheric CO₂ concentration shows a **strong increasing long-term trend**.
* A clear **annual seasonal pattern** is present.
* The seasonal component repeats approximately every **12 months**.
* The residual component represents irregular fluctuations not explained by the trend or seasonal pattern.
* The monthly average CO₂ concentration is generally higher during the earlier part of the year and lower during the later months.
* The highest average monthly CO₂ concentration in this analysis occurs around **May**, while the lowest occurs around **September–October**.

---

## 📁 Project Structure

```text
Monthly-CO2-Time-Series/
│
├── mauna_loa_co2_monthly_mean_data.csv
├── Mauna_Loa_CO2_TimeSeries.ipynb
└── README.md
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone <your-repository-url>
```

### 2. Open the project folder

```bash
cd Monthly-CO2-Time-Series
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open

```text
Mauna_Loa_CO2_TimeSeries.ipynb
```

### 5. Run the notebook cells sequentially.

---

## 📦 Required Libraries

Install the required Python libraries using:

```bash
pip install pandas numpy matplotlib statsmodels
```

---

## 📌 Conclusion

The analysis demonstrates that the Mauna Loa atmospheric CO₂ time series contains both a **strong long-term upward trend** and a **repeating annual seasonal pattern**.

Moving averages and seasonal decomposition provide useful ways to separate and understand the different components of a real-world time series.

---

## 👩‍💻 Experiment

**Course:** Time Series Analysis and Forecasting
**Experiment:** Monthly CO₂ Concentration Analysis
**Environment:** Python / Jupyter Notebook
