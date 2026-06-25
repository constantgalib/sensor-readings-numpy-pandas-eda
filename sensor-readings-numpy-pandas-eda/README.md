# Smart City Sensor Readings: NumPy, Pandas and Visualization Project

This project is a beginner-friendly exploratory data analysis notebook built with a sensor readings dataset.

## Project Goal

The goal is to practice and demonstrate elementary but essential data-analysis concepts:

- NumPy arrays and attributes
- NumPy indexing, slicing, arithmetic and logical operations
- Conditional counting and boolean masking
- Pandas DataFrame loading and inspection
- Creating and deleting columns
- Sorting and filtering DataFrames
- GroupBy aggregation
- Matplotlib visualizations
- Seaborn visualizations

## Dataset

The dataset contains environmental sensor readings such as:

- Temperature
- Humidity
- Light
- Timestamp
- Sensor board ID
- Location
- Latitude and longitude

## Files

- `Sensor_readings.csv` — raw dataset
- `sensor_readings_numpy_pandas_eda.ipynb` — main notebook
- `README.md` — project description

## Main Libraries

```python
numpy
pandas
matplotlib
seaborn
```

## Skills Demonstrated

### NumPy

- Creating arrays from DataFrame columns
- Checking `.shape`, `.ndim`, `.size`, `.dtype`, `.nbytes`
- Indexing and slicing
- Arithmetic operations
- Mathematical functions such as mean, median, min, max and standard deviation
- Logical conditions and boolean masking

### Pandas

- Reading CSV files
- Inspecting data using `.head()`, `.info()`, `.describe()`
- Checking missing values
- Creating new columns
- Dropping unnecessary columns
- Sorting data
- Filtering data
- Conditional counting
- Grouping and aggregating data

### Visualization

Matplotlib:

- Line plot
- Histogram
- Scatter plot
- Bar plot

Seaborn:

- Scatterplot with hue
- Count plot
- Bar plot
- Box plot
- Correlation heatmap

## How to Run

1. Clone the repository.
2. Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

3. Open the notebook:

```bash
jupyter notebook sensor_readings_numpy_pandas_eda.ipynb
```

## Suggested GitHub Repository Name

```text
sensor-readings-numpy-pandas-eda
```

## Possible Extensions

- Add time-series forecasting
- Build anomaly detection for unusual sensor readings
- Create an interactive dashboard using Plotly, Dash or Streamlit
- Train a machine learning model to predict temperature or humidity