# US COVID-19 Data Analysis

## Overview
This project analyzes COVID-19 data for US states using R. The dataset is sourced from The New York Times COVID-19 data repository, specifically the `us-states.csv` file. The analysis focuses on visualizing and understanding the trends in COVID-19 cases for different states over time.

## Files
1. **us-states.csv:**  
   - This CSV file contains COVID-19 data, including information about the date, state, FIPS code, cumulative cases, and cumulative deaths.

2. **US_data.R:**  
   - This R script file contains the code for loading, cleaning, and visualizing the COVID-19 data.

3. **US_data.html:**  
   - This HTML file is the knitted report generated from the R script. It includes interactive visualizations and insights.

4. **README.md:**  
   - The file you are currently reading, providing essential information about the project.

## How to Run the Analysis
1. Ensure you have R installed on your machine.
2. Download the COVID-19 dataset from [The New York Times GitHub repository](https://github.com/nytimes/covid-19-data) and save it as `us-states.csv`.
3. Open the `US_data.R` script in your preferred R environment.
4. Run the script to perform the analysis.
5. View the results in the generated `US_data.html` report.

## Dependencies
- tidyverse
- plotly
- data.table
- ggplot2
- maps
- dplyr
- tidyr
- lubridate

Install the dependencies using the following R command:
```R
install.packages(c("tidyverse", "plotly", "data.table", "ggplot2", "maps", "dplyr", "tidyr", "lubridate"))
