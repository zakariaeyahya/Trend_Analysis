# Trend Analysis

## Description:
<p>This Shiny application aims to visualize and explore trends in demographics and income based on the provided dataset. 
Users can filter the data by country and then explore various demographic information. 
The application allows users to select different variables and plot types to analyze trends effectively.</p>

## How to Use:

<ol>
    <li><strong>Launch the Application:</strong> Upon opening the application, users are greeted with a title "Trend in Demographics and Income" and a brief description of the purpose of the application.</li>
    <li><strong>Select Country:</strong> Users can choose a country from the dropdown menu provided. The available options include "United-States," "Canada," "Mexico," "Germany," and "Philippines."</li>
    <li><strong>Continuous Variable Analysis:</strong> Users can select a continuous variable ("age" or "hours_per_week") and choose between a histogram or a boxplot for visualization. The plot on the right side dynamically updates based on the selected variables and plot type.</li>
    <li><strong>Categorical Variable Analysis:</strong> Users can select a categorical variable ("education," "workclass," or "sex") to view a bar chart on the right side. Additionally, users can check the box to stack the bar chart, combining income levels into one graph.</li>
</ol>

## Files:

<ul>
    <li><strong>ui.R:</strong> Contains the user interface (UI) code for the Shiny application.</li>
    <li><strong>server.R:</strong> Contains the server-side logic for the Shiny application, including data processing and rendering plots.</li>
</ul>

## Data:
<p>The application reads data from the "adult.csv" file, which contains demographic and income information.</p>

## License:
<p>This project is licensed under the <strong>YAHYA</strong> license.</p>

## Screenshot:
<img src="Capture%20d’écran%202024-04-20%20165857.png" alt="Application Screenshot" style="max-width:100%; height:auto;">

## Contact:
<p>For any inquiries, please reach out via email or LinkedIn:</p>

<ul>
    <li>Email: <a href="mailto:zakariae.yh@gmail.com">zakariae.yh@gmail.com</a></li>
    <li>LinkedIn: <a href="https://www.linkedin.com/in/zakariae-yahya" target="_blank">Zakariae Yahya</a></li>
</ul>
