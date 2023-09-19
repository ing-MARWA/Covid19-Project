# Covid19-Project

# COVID-19 Pandemic Data Analysis

This project aims to analyze the COVID-19 pandemic data from different perspectives and visualization techniques. The data gathered includes information on confirmed cases, deaths, recoveries, active cases, and other related factors. The analysis is performed using Python's data manipulation and visualization libraries such as NumPy, Pandas, Matplotlib, Seaborn, and Plotly.

## Getting Started

To get started, clone this repository to your local machine and ensure that the required Python libraries are installed. The data is available in CSV format, which will be read into Pandas DataFrames for analysis. 

## Data Cleaning

Before performing any analysis, the data must be cleaned and transformed appropriately. The project deals with five files as follows: 
- `country_wise_latest.csv`: Provides data related to each country.
- `day_wise.csv`: Provides data for each day.
- `covid_19_clean_complete.csv`: Provides data for each day related to the country, province/state.
- `full_grouped.csv`: Provides the total number of cases and deaths for each country.
- `worldometer_data.csv`: Provides data from the 'worldometer' website regarding countries.

Each file is checked for missing values, and the percentage of null values is calculated. Further, any column with more than 70% null values is dropped. Necessary changes are made where countries have more than one name, and missing values are filled in as well. 

## Analysis

### Country Wise Data Analysis 
This section includes:
- Boxplot to look at the outliers.
- Heatmap to show correlation between cases.
- Top 20 countries for confirmed cases, deaths, recoveries, and active cases.

### Day Wise Data Analysis
This section includes:
- Graphs showing the number of different cases over time.
- Histogram to describe the number of deaths over time.

### Combined Data Analysis
This section includes:
- Top 20 countries for confirmed cases over population percentage.
- Top 20 countries for recovered over confirmed percentage.
- Top 20 countries for active cases over confirmed percentage.
- Top 20 countries for deaths over confirmed percentage.

## Conclusion

The COVID-19 pandemic has affected the world's population immensely. With the help of these analyses, we can interpret the trends of the coronavirus on a global, national, provincial/state, and individual level, providing governments and health institutions with valuable insights to control the spread of the virus.

## Acknowledgments

This project could not have been completed without the extensive documentation of the various libraries utilized and the availability of the data used. We would like to express our gratitude to the developers who worked on the libraries and the open-source data contributors who were paramount in making the analysis possible.

## References

- Pandas Documentation [https://pandas.pydata.org/pandas-docs/stable/]
- NumPy [https://numpy.org/]
- Matplotlib [https://matplotlib.org/]
- Seaborn [https://seaborn.pydata.org/]
- Plotly [https://plotly.com/python/]
- COVID-19 data repository maintained by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University [https://github.com/CSSEGISandData/COVID-19]   
                           
                     
