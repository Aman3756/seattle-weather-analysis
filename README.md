# Weather Trend Analysis of Delhi

## Objective
To analyse temperature, humidity and other weather trends in Delhi using Python, and to find seasonal and yearly patterns in the data.

## Dataset
- **Source:** Daily Delhi Climate dataset (Kaggle), file `DailyDelhiClimateTrain.csv`
- **Columns:** date, meantemp, humidity, wind_speed, meanpressure
- **Changes made to the dataset:**
  - Converted the `date` column to datetime format
  - Removed duplicate rows
  - Removed unrealistic `meanpressure` values (outliers)
  - Added new columns: `year`, `month`, `month_name`, `season`, `temp_category`
- The cleaned dataset is saved as `cleaned_weather_data.csv`

## Tools Used
- Python
- Pandas and NumPy (data handling)
- Matplotlib and Seaborn (visualisation)
- Microsoft Excel (initial exploration: filters, pivot table, line chart)
- Google Colab and GitHub

## Project Steps
1. Initial exploration of the data in Excel
2. Loading the data and checking its structure in Python
3. Data cleaning and adding new columns
4. Visualisation: temperature trend, monthly and yearly averages, seasonal boxplot, humidity vs temperature, correlation heatmap
5. Key findings and conclusion

## Key Findings
- Temperature follows a clear yearly cycle, with June being the hottest month and January the coldest.
- Yearly average temperature stayed fairly stable from 2013 to 2016, with no strong warming trend visible.
- Humidity has a negative relationship with temperature: hot months are drier.
- Summer shows the widest spread of temperatures, while the monsoon season is the most stable.

## Files in this Repository
- `Delhi_Weather_Analysis.ipynb`: the main Colab notebook
- `DailyDelhiClimateTrain.csv`: original dataset
- `cleaned_weather_data.csv`: cleaned dataset
