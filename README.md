# Analyzing 6 Years of GPS Fitness Tracker Data

An exploratory data analysis of personal running data (2012–2018) exported from [Runkeeper](https://runkeeper.com/), covering data cleaning, visualization, trend analysis, and goal tracking.

## Dataset
- **508 activities** across Running, Cycling, Walking, and Unicycling
- Key features: Distance, Duration, Average Speed, Climb, Average Heart Rate
- Source: Runkeeper CSV export

## Tools
Python · Pandas · Matplotlib · Statsmodels

## Analysis Highlights

- Cleaned raw data: removed unused columns, imputed missing heart rate values using activity-type means
- Explored weekly and annual running statistics (2015–2018)
- Decomposed weekly distance trends to assess long-term progress
- Visualized heart rate distribution across training intensity zones
- Tracked annual distance goals (target: 1,000 km/year)

## Visualizations

### Running Metrics Over Time
<!-- Save the Average Heart Rate scatter plot (Task 4) as images/running_metrics.png -->
![Running Metrics](images/running_metrics.png)

### Distance & Heart Rate Averages
<!-- Save the two-subplot figure with average lines (Task 6) as images/averages_plot.png -->
![Averages](images/averages_plot.png)

### Annual Distance vs Goal
<!-- Save the annual totals plot with green/yellow zones (Task 7) as images/annual_totals.png -->
![Annual Totals](images/annual_totals.png)

### Weekly Distance Trend
<!-- Save the trend decomposition plot (Task 8) as images/weekly_trend.png -->
![Trend](images/weekly_trend.png)

### Heart Rate by Training Zone
<!-- Save the color-coded HR histogram (Task 9) as images/hr_zones.png -->
![HR Zones](images/hr_zones.png)

## Quick Stats

| Metric | Value |
|---|---|
| Total runs | 459 |
| Total km run | 5,224 km |
| Longest run | 38.32 km |
| Total climb | 57,278 m |
| Shoes used | 7 pairs |

## How to Run

```bash
git clone https://github.com/reshma-sajan/Project---Analysis-of-Fitness-Data.git
cd Project---Analysis-of-Fitness-Data
pip install pandas matplotlib statsmodels
jupyter notebook "Analysis of Fitness Data.ipynb"
```
