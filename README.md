# London-Housing-Data-Analysis 
London Housing Data Analysis notebook project using data from ***1995 to 2019***. Created using Google Colab.

## Description

This project analyzes London housing data from 1995 to 2019, exploring trends in average house prices, sales volume, and crime rates across different London boroughs. The dataset is available as a CSV file and was downloaded from **Kaggle**.

## Dataset

The dataset contains the following information:

- **Date:** Monthly timestamp from 1995 to 2019
- **Area:** London borough
- **Average Price:** Average house price for the month and area
- **Code:** Area code
- **Houses Sold:** Number of houses sold in the month and area
- **No. of Crimes:** Number of crimes committed in the month and area

## Analysis Performed

The notebook performs the following analysis:

1. **Data Cleaning:** Handles missing values and converts the 'Date' column to datetime format.
2. **Temporal Analysis:** Extracts year and month from the 'Date' column for time-based analysis.
3. **Descriptive Statistics:** Calculates counts, identifies null values, and generates a heatmap to visualize missing data.
4. **Crime Analysis:** Filters and analyzes records with zero crimes, calculates frequency, and determines maximum and minimum crime rates per area.
5. **Price Analysis:** Calculates maximum and minimum average prices per year for England, and counts areas with average prices below 100,000.

## How to Use

1. Open the notebook in Google Colab.
2. Install any necessary libraries (if not pre-installed).
3. Run the code cells sequentially to perform the analysis.
4. Explore the results and visualizations.

## Requirements

- Python 3
- Pandas
- Seaborn
- Matplotlib

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests for improvements or additional analysis.
