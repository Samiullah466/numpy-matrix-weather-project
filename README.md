# numpy-matrix-weather-project

# Weather Data Analysis using NumPy

This project focuses on matrix manipulation and numerical analysis using NumPy, a powerful numerical computing library in Python. The dataset represents simulated temperature readings recorded every hour for 10 days, resulting in a 10x24 matrix.

## 📌 Project Steps

### ✅ Step 1: Data & Matrix Manipulation
We begin by simulating a dataset that resembles real-world hourly temperature readings over a period of 10 days.

### ✅ Step 2: Load the Data
Data is generated or loaded using NumPy arrays and reshaped appropriately for matrix operations.

### ✅ Step 3: Basic Exploration
Initial exploration includes:
- Checking shape and type
- Slicing and indexing
- Verifying sample values

### ✅ Step 4: Handle Missing Values
Some values are set to `np.nan` to simulate missing data. These are handled using:
- `np.nanmean()`
- `np.nan_to_num()`

### ✅ Step 5: Data Analysis
Basic statistical analysis is performed on the matrix, including:
- Mean temperature
- Minimum and maximum temperatures
- Daily and hourly trends

### ✅ Step 6: NumPy Matrix Exercises

- 🔁 Reshape the flat temperature array into a 10x24 matrix
- 📊 Normalize the matrix using:  
  `(value - min) / (max - min)`
- 🎯 Apply a custom mask/filter to extract temperature values above a threshold (e.g., 35°C)

---

## 🧠 Final Challenge: Custom Summary Function

A custom function `daily_summary(matrix)` is implemented.  
This function accepts a NumPy matrix of shape (10, 24) and returns a dictionary containing daily summaries:

```python
{
    'day_1': {'min': ..., 'max': ..., 'mean': ...},
    'day_2': {'min': ..., 'max': ..., 'mean': ...},
    ...
}
