# Page View Time Series Visualizer

A freeCodeCamp Data Analysis with Python project.

## What it does

`time_series_visualizer.py` visualizes daily page views of the freeCodeCamp
forum (`fcc-forum-pageviews.csv`) using Pandas, Matplotlib and Seaborn:

- Cleans the data by removing the top and bottom 2.5% of page views
- `draw_line_plot()` draws a line chart of daily page views
- `draw_bar_plot()` draws average daily page views per month, grouped by year
- `draw_box_plot()` draws year-wise (trend) and month-wise (seasonality) box plots

## Run

    python main.py

## Requirements

- Python 3
- pandas, matplotlib, seaborn
