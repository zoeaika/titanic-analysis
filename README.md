# Titanic Data Analysis 🚢

This project analyzes the Titanic dataset using Python, pandas, matplotlib, and seaborn.

## 📁 Files Included

- `titanic_analysis.py`: Python script containing all analysis and visualizations.
- (Optional) `titanic_analysis.ipynb`: Jupyter Notebook version.
- Visual output plots (PNG files if saved): 
  - `line_chart_age_trend.png`
  - `bar_chart_fare_pclass.png`
  - `histogram_age_distribution.png`
  - `scatterplot_fare_vs_age.png`

## 📊 What’s in the Analysis

### 1. Data Loading & Cleaning
- Loads Titanic dataset from a public URL.
- Handles missing values (e.g., fills missing age with mean).

### 2. Basic Statistics
- Summary statistics using `.describe()`.
- Grouped statistics:
  - Mean Age and Fare by `Pclass`
  - Mean Age and Fare by `Sex`
  - Combined grouping by `Pclass` and `Sex`

### 3. Visualizations
- **Line Chart**: Age trend by Passenger ID
- **Bar Chart**: Average Fare by Passenger Class
- **Histogram**: Age distribution
- **Scatter Plot**: Age vs Fare (colored by survival)

All plots are labeled and styled using matplotlib and seaborn.

## 📌 Observations

- 1st class passengers paid higher fares and tended to be older.
- Women, on average, paid higher fares than men.
- Most passengers were between 20–40 years old.
- Passengers who paid more were slightly more likely to survive.

## 🔧 Technologies Used

- Python 🐍
- pandas
- matplotlib
- seaborn
- Jupyter Notebook 

## 🔗 Dataset Source

- [Titanic dataset from DataScienceDojo (GitHub)](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

---

## 📎 How to Run

```bash
# Install required packages if not already installed
pip install pandas matplotlib seaborn

# Run the script
python titanic_analysis.py
