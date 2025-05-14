# Data Analysis Project: School Performance Metrics

## Project Overview
This project analyzes educational/school data through three key tasks: data exploration, statistical analysis, and visualization. The workflow covers the complete data analysis pipeline from loading datasets to generating actionable insights.

## Tasks Breakdown

### Task 1: Data Loading and Exploration
- Loads school performance dataset (CSV format)
- Performs initial data inspection using `.head()` and `.info()`
- Checks for and handles missing values
- Outputs dataset structure and cleaning summary

### Task 2: Department-wise Statistical Analysis
- Computes descriptive statistics (mean, median, standard deviation)
- Analyzes metrics by department/grade level
- Identifies key patterns:
  - Highest performing departments
  - Experience-performance correlations
  - Salary distributions

### Task 3: Educational Data Visualization
Generates four publication-ready plots:
1. **Student Progress Line Chart**: Tracks test scores across time/students
2. **Department Comparison Bar Chart**: Compares average scores by group
3. **Score Distribution Histogram**: Shows grade frequency distribution
4. **Correlation Scatter Plot**: Examines math vs reading performance

## How to Use
1. Ensure required packages are installed:
   ```bash
   pip install pandas matplotlib seaborn numpy
