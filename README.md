# Exploratory Data Analysis of Solar Radiation Data

This project involves exploratory data analysis (EDA) on solar radiation data collected from various locations, with the objective of cleaning, analyzing, and visualizing the data. The analysis includes summary statistics, data quality checks, correlation analysis, time series analysis, and various visualizations.

## Code Overview

- The code is written in Python and relies on several libraries for data manipulation and visualization, including `pandas`, `numpy`, `seaborn`, and `matplotlib` .
- The code is structured to load CSV data files, clean them, and perform EDA on each dataset.
- The EDA process includes calculating summary statistics, creating time-series visualizations, correlation heatmaps, histograms, scatter plots, and box plots.

## Functions

- **`clean_data(data)`**: Cleans the data by handling missing values, duplicates, and invalid data. It converts infinite values to NaN, imputes missing numeric values with the column mean, removes duplicates, and handles entirely null columns.
- **`perform_eda(data, location_name)`**: Performs exploratory data analysis on the dataset for a specific location. This includes:

  - Summary statistics
  - Data quality checks
  - Time series analysis
  - Correlation analysis
  - Wind analysis
  - Temperature analysis
  - Histograms, box plots, and scatter plots

- **`load_csv_data(file_path)`**: Loads CSV data from a specified file path with error handling to check for file existence and parsing issues.

## Requirements

To run this project, ensure you have the following packages installed:

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `os`

Ensure your Python environment is set up with these packages before executing the code.

## How to Run

To execute the code and perform EDA:

1. Clone the project repository and navigate to the code directory.
2. Ensure the necessary CSV data files are available in the same directory as the script.

## Instructions

To run the code, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Tewodros01/10_Week0_Challenge_Data_Analysis.git
   ```

2. Navigate to the project directory::

   ```bash
   cd <project-directory>
   ```

3. Install the required Python packages::

   ```bash
   pip install -r requirements.txt
   ```

4 .You can use Jupyter notebooks
