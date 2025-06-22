# Delhi Metro Data Analysis

## Overview

This Python script utilizes Pandas, Folium, and Plotly to perform an analysis of Delhi Metro data. The analysis covers station distribution, opening years, line statistics, and station layouts, presenting the findings through interactive maps and visualizations.

## Code Structure

- `delhi_metro.csv`: Input data file containing information about Delhi Metro stations.
- `README.md`: This file providing an overview and instructions for the script.

## Dependencies

Ensure you have the following libraries installed:

- `pandas`
- `folium`
- `plotly`

Install them using:

```bash
pip install pandas folium plotly
```

## Data Exploration
The script reads the data from delhi_metro.csv, performs checks for missing values, and converts the 'Opening Date' column to datetime format.

## Maps and Visualizations
Delhi Metro Map with Line Tooltip: Utilizes Folium to display a map with colored markers for each metro station, indicating the metro line. Tooltip includes station name and line.
Number of Metro Stations Opened Each Year: Visualizes the count of metro stations opened each year using Plotly Express.
Metro Line Analysis: Presents bar plots for the number of stations per metro line and the average distance between stations for each line.
Distribution of Delhi Metro Station Layouts: Displays a bar plot illustrating the distribution of station layouts.

## Customization
Modify the line_colors dictionary to define a color scheme for each metro line.
Feel free to explore and customize the script for further analysis or additional visualizations.

## License
This Delhi Metro Data Analysis script is open-source and distributed under the MIT License. You are encouraged to modify and share the code!
