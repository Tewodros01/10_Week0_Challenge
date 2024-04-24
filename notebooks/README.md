Solar Radiation Data Analysis
Project Overview
This project involves exploratory data analysis (EDA) on solar radiation data collected from various locations. The objective is to gain insights into weather patterns, solar energy generation, and related factors through statistical analysis and visualizations. This project uses Python libraries like Pandas, Seaborn, and Matplotlib to perform data cleaning and EDA.

Project Structure
data/: Contains the source CSV files used for analysis.
notebooks/: Contains Jupyter Notebooks for performing data analysis.
results/: Stores visualizations and output files generated during analysis.
README.md: This document, providing an overview of the project.
Code Overview
The primary notebook in this project includes:

Data Loading: Loading data from CSV files and handling errors.
Data Cleaning: Removing duplicates, handling missing values, and converting invalid data.
Exploratory Data Analysis:
Summary statistics
Time-series analysis
Correlation analysis
Wind analysis
Temperature analysis
Various visualizations (scatter plots, box plots, etc.)
Usage Instructions
To run the Jupyter Notebook and perform the EDA:

Ensure you have Python 3.x installed.
Install the required libraries: pandas, seaborn, matplotlib, and numpy.
Clone this repository and navigate to the project directory.
Start Jupyter Notebook with the following command:

Visualizations
During the EDA, various visualizations are generated, including:

Time-series plots of solar radiation and temperature data.
Correlation heatmaps showing relationships between variables.
Box plots, scatter plots, and histograms for additional insights.
Error Handling
The code includes error handling to manage issues like missing files, parsing errors, and invalid data formats. If you encounter errors, check the CSV files for anomalies or corrupted data.
