## Climate Change and its Consequences

This is my final project at Le Wagon Data Analyst Bootcamp, where we focused on investigating the relationship between CO2 emissions, global warming, and their impact. The project was completed in a group of five, and this repository contains my individual contributions.

**Objective**

This project aims to explore the connection between the significant increase in CO2 emissions due to human industrial activity and its correlation with global warming. Additionally, we examine the impact of global warming on natural disasters and its potential correlation with inflation.

Datasets

I utilized several datasets from [Kaggle](https://www.kaggle.com/) and other sources for this project. 

Specifically, I focused on the [temperature](https://www.kaggle.com/datasets/mdazizulkabirlovlu/all-countries-temperature-statistics-1970-2021) dataset and the [disasters](https://www.kaggle.com/datasets/brsdincer/all-natural-disasters-19002021-eosdis) dataset. 

To establish the connection between these datasets, I created a file in Google Sheets containing international country names and codes to facilitate table joins. Additionally, I created a CSV file named ["disaster_global_temp"](https://github.com/Krisztana/Climate-Change-and-it-s-consequences/blob/main/disaster_global_temp.csv) that combines relevant data from the temperature and disaster datasets.

To forecast CO2 emissions, I utilized the ["temperature_gaz_dataset"](https://github.com/Krisztana/Climate-Change-and-it-s-consequences/blob/main/temperature_gaz_dataset.xlsx) available in the repository.

**Methodology**

The following techniques and tools were employed in this project:

* Jupyter Notebook: The majority of the analysis was conducted using Jupyter Notebook, providing an interactive and collaborative environment for data exploration and analysis.

* Libraries: I leveraged various libraries for data manipulation, visualization, and modelling, including:

   * Pandas: Used for data manipulation and analysis.
   * NumPy: Employed for mathematical operations and array manipulation.
   * Matplotlib and Seaborn: Utilized for creating static visualizations and enhanced data visualization.
   * Calendar: Employed for working with dates and calendar-related operations.
   * Wordcloud: Utilized for generating word clouds from textual data.
   * ipywidgets: Used to create interactive elements, such as continent filter options for charts.

* Data Interpolation: I employed the interpolate() function with the "backfill" method to fill in missing values in the data by interpolating values based on neighbouring data points.

* Correlation Analysis: I used the .corr() method to explore the relationships between variables and assess the strength and direction of their correlations.

* Time Series Forecasting: I employed the ForecasterAutoreg from the skforecast library for time series forecasting tasks.

* Linear Regression: I utilized the LinearRegression model from the sklearn library for linear regression analysis.

**Conclusion**

In conclusion, the analysis highlights the following key findings:

* CO2 Emissions and Global Warming: A strong correlation was observed between CO2 emissions and global warming, indicating that the release of CO2 contributes to the increase in global temperatures. Historical data, including the industrial revolution and the rise of coal-fired power stations, further support this correlation.

* Global Warming and Natural Disasters: There is a notable correlation between global warming and the occurrence of storms and floods. As global temperatures rise, the frequency and intensity of these natural disasters tend to increase.

* Regional Disparities: Despite Europe and America having higher CO2 emissions, Asia and Africa experience a greater impact from natural disasters. This suggests that the consequences of climate change are not evenly distributed across regions.

These findings emphasize the urgency of collective action to reduce CO2 emissions and address the challenges posed by global warming. By adopting sustainable practices and implementing global policies, we can strive to minimize the adverse effects of climate change on vulnerable regions.
