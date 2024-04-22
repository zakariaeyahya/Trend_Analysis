# Trend_Analysis
## Description:
This Shiny application aims to visualize and explore trends in demographics and income based on the provided dataset. Users can filter the data by country and then explore various demographic information. The application allows users to select different variables and plot types to analyze trends effectively.

## How to Use:

Upon opening the application, users are greeted with a title "Trend in Demographics and Income" and a brief description of the purpose of the application.
Select Country:
Users can choose a country from the dropdown menu provided. The available options include "United-States," "Canada," "Mexico," "Germany," and "Philippines."
Continuous Variable Analysis:
Users can select a continuous variable ("age" or "hours_per_week") and choose between a histogram or a boxplot for visualization. The plot on the right side dynamically updates based on the selected variables and plot type.
Categorical Variable Analysis:
Users can select a categorical variable ("education," "workclass," or "sex") to view a bar chart on the right side. Additionally, users can check the box to stack the bar chart, combining income levels into one graph.
## Files:

ui.R: Contains the user interface (UI) code for the Shiny application.
server.R: Contains the server-side logic for the Shiny application, including data processing and rendering plots.
## Data:

The application reads data from the "adult.csv" file, which contains demographic and income information.

## License:

This project is licensed under the [insert license] license.
