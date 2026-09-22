# 3. Introduction to Pandas

## Overview

This notebook introduces Pandas for data manipulation, cleaning, analysis, reshaping, time-series processing, visualization, and performance optimization.

The Colab was executed completely with its inputs and outputs saved. The video walkthrough focuses on the most important Pandas concepts, explains the key code blocks, and discusses what the outputs and plots actually show.

---

## Links

- **Executed Colab:** [Introduction to Pandas - Executed](https://colab.research.google.com/drive/1V2vupjBPAtfHiMEU4XsTYh66EhUkIUEk?usp=sharing)
- **YouTube Walkthrough:** [Introduction to Pandas - Video Walkthrough](https://youtu.be/gcgWxWOnAOo)

---

## Topics Covered

### Pandas Foundations
- Series and DataFrames
- Indexes and label alignment
- Data types and schema inspection
- `head()`, `tail()`, `sample()`, `info()`, and `describe()`

### Indexing and Selection
- Column selection
- `loc`
- `iloc`
- Boolean masks
- `query()`
- Scalar access using `at` and `iat`
- Difference between label-based and position-based indexing

### Data Cleaning
- Detecting missing values
- `dropna()`
- `fillna()`
- Group-based imputation
- Duplicate detection and removal
- Fixing invalid values
- Converting incorrect data types
- Cleaning string columns

### Data Types and Memory
- Numeric conversion
- Datetime conversion
- Categorical data
- Memory usage
- Benefits of using `category` for repeated text values

### Vectorized Operations
- Column-wise arithmetic
- Creating new calculated columns
- `np.where`
- `np.select`
- String operations using `.str`
- Datetime operations using `.dt`
- Why vectorized operations are faster than row-by-row loops

### GroupBy and Aggregation
- Split-Apply-Combine
- `groupby()`
- `agg()`
- `transform()`
- `apply()`
- Group-level totals, averages, and counts
- Adding group-level statistics back to individual rows

### Reshaping Data
- `pivot()`
- `pivot_table()`
- `melt()`
- `stack()`
- `unstack()`
- Long vs wide data formats

### Combining DataFrames
- `merge()`
- `join()`
- `concat()`
- Inner, left, right, and outer joins
- Handling different join-key names
- Merge validation
- Understanding duplicate-key row multiplication

### Time-Series Analysis
- Datetime indexes
- Partial-date selection
- `resample()`
- `asfreq()`
- Upsampling and filling missing timestamps
- Rolling averages
- Expanding averages
- `shift()`
- `diff()`
- `pct_change()`
- Time-zone localization and conversion

### Data Visualization
- Pandas `.plot()`
- Bar charts
- Horizontal bar charts
- Histograms
- Box plots
- Scatter plots
- Area charts
- Stacked bar charts
- Correlation heatmaps
- Scatter matrices
- Understanding what the x-axis, y-axis, bars, dots, and colors represent

### Statistics and Analysis
- Summary statistics
- Correlation
- Revenue calculations
- Percent change
- Rolling averages
- Weekend vs weekday comparisons
- Product and regional revenue analysis

### Performance and Efficiency
- Vectorization vs `apply()` vs `iterrows()`
- Timing comparisons
- `eval()` and `query()` performance
- Chunked CSV processing
- Memory-efficient data handling

### Final Capstone
- Cleaning and transforming the dataset
- Filtering weekend transactions
- Grouping by region and product
- Calculating revenue share
- Producing the final weekend revenue-mix table
- Visualizing the result using a heatmap

---

## Key Takeaways

This notebook demonstrates how Pandas can be used to take raw tabular data through a complete data-analysis workflow.

The main concepts include:

- Inspecting data before analysis
- Understanding the importance of indexes and data types
- Cleaning missing, duplicated, and inconsistent data
- Selecting and filtering rows correctly
- Performing fast vectorized calculations
- Summarizing data with GroupBy
- Reshaping data between long and wide formats
- Safely combining datasets using joins
- Working with time-series data
- Building and interpreting plots
- Improving performance and memory usage

---

## Why Pandas Matters for Data Science

Pandas is one of the main tools used for preparing and analyzing structured data before Machine Learning.

It is commonly used for:

- Data cleaning
- Exploratory Data Analysis
- Feature engineering
- Aggregation
- Joining multiple datasets
- Time-series analysis
- Preparing data before model training

Understanding these concepts makes it easier to work with real-world datasets and build reliable Machine Learning pipelines.

---

## Repository Files

- `03 Introduction to Pandas - Executed.ipynb`
- `README.md`
- [YouTube Video Walkthrough](https://youtu.be/gcgWxWOnAOo)

---

## Conclusion

This notebook provides a practical introduction to Pandas and shows how raw tabular data can be inspected, cleaned, transformed, analyzed, combined, and visualized.

The final analysis brings the major concepts together by calculating and visualizing weekend revenue contribution by product and region.
