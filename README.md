# WHR2021-Analysis
Exploratory Data Analysis (EDA) of World Happiness Report Data 2021

This repository contains Python code for analyzing the World Happiness Report (2021) data. The report is a landmark survey of the state of global happiness and well-being. The code is written in Python and uses the following libraries:
`numpy`
`pandas`
`matplotlib.pyplot`
`seaborn`
`plotly.express`
`plotly.graph_objects`
`sklearn.linear_model`
`seaborn`

The code reads the `WHRData2021.csv` file, which contains the data of the report, and performs exploratory data analysis on it. The following are the main steps that are performed in the code:

-Importing the necessary libraries
-Reading the data from the CSV file using Pandas
-Cleaning the data by removing unnecessary columns and rows containing null values
-Visualizing the data using scatter plots, bar plots, and heat maps
-Performing linear regression on selected features
-Creating box plots to analyze the relationship between institutional trust and female head of government

## Installation
To run the code, you need to have Python 3 and the required libraries installed on your machine. To install the libraries, you can use the following command:
```bash
pip install numpy pandas matplotlib seaborn plotly scikit-learn

```
## Usage
To use the code, simply clone the repository and run the `WHRData2021.ipynb` notebook in Jupyter Notebook or any other Python environment of your choice.

## Flow
This code is an analysis of the World Happiness Report data for 2021. The libraries used in this code are numpy, pandas, matplotlib, seaborn, plotly express, and plotly graph objects.
The first step is to import the required libraries and then read the WHRData2021.csv dataset using pandas. After that, the data is cleaned and preprocessed by removing unnecessary columns and rows with null values.
The analysis starts with a scatter plot of Median age against Gini coefficient of income for different countries. The scatter plot is then enhanced with a trendline using plotly express. Next, a bar chart is plotted to compare the population of the top 10 countries in 2019 and 2020. A scatter plot is then used to show the relationship between Population 2020 and Median age for different countries.
The code then focuses on the COVID-19 pandemic and plots a bar chart of the top 10 countries with the most deaths per 100,000 population in 2020. This is followed by a heatmap that shows the correlation matrix of the dataset. Another scatter plot is then plotted to explore the relationship between Median age, COVID-19 deaths per 100,000 population in 2020, and Population 2020.
The code then plots a histogram of the Median age for different countries. A bar chart is then plotted to show the top 10 countries with the highest Index of institutional trust. Finally, the code uses LinearRegression and seaborn to plot a scatter plot of Median age against Gini coefficient of income and a box plot to compare the Index of institutional trust for female head of government and non-female head of government.
Overall, this code is a good example of data analysis using various libraries and techniques. The README provides a clear and concise overview of the code and its purpose.

## Contributing
If you find any issues with the code or have any suggestions for improvement, feel free to open an issue or submit a pull request.
