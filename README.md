<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trend Analysis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 0;
            background-color: #f4f4f4;
            line-height: 1.6;
        }
        h1, h2, h3 {
            color: #333;
        }
        .container {
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .contact-info {
            margin-top: 20px;
        }
        .contact-info a {
            color: #0066cc;
            text-decoration: none;
        }
        .contact-info a:hover {
            text-decoration: underline;
        }
        img {
            margin-top: 20px;
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Trend Analysis</h1>
        <h2>Description:</h2>
        <p>
            This Shiny application aims to visualize and explore trends in demographics and income based on the provided dataset. 
            Users can filter the data by country and then explore various demographic information. 
            The application allows users to select different variables and plot types to analyze trends effectively.
        </p>
        
        <h2>How to Use:</h2>
        <ol>
            <li><strong>Launch the Application:</strong> Upon opening the application, users are greeted with a title "Trend in Demographics and Income" and a brief description of the purpose of the application.</li>
            <li><strong>Select Country:</strong> Users can choose a country from the dropdown menu provided. The available options include "United-States," "Canada," "Mexico," "Germany," and "Philippines."</li>
            <li><strong>Continuous Variable Analysis:</strong> Users can select a continuous variable ("age" or "hours_per_week") and choose between a histogram or a boxplot for visualization. The plot on the right side dynamically updates based on the selected variables and plot type.</li>
            <li><strong>Categorical Variable Analysis:</strong> Users can select a categorical variable ("education," "workclass," or "sex") to view a bar chart on the right side. Additionally, users can check the box to stack the bar chart, combining income levels into one graph.</li>
        </ol>
        
        <h2>Files:</h2>
        <ul>
            <li><strong>ui.R:</strong> Contains the user interface (UI) code for the Shiny application.</li>
            <li><strong>server.R:</strong> Contains the server-side logic for the Shiny application, including data processing and rendering plots.</li>
        </ul>
        
        <h2>Data:</h2>
        <p>
            The application reads data from the "adult.csv" file, which contains demographic and income information.
        </p>
        
        <h2>License:</h2>
        <p>
            This project is licensed under the Copyright (c) 2024 YAHYA license.
        </p>

        <img src="Capture d’écran 2024-04-20 165857.png" alt="Application Screenshot">
        
        <div class="contact-info">
            <p>Contact: <a href="mailto:zakariae.yh@gmail.com">zakariae.yh@gmail.com</a></p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/zakariae-yahya" target="_blank">Zakariae Yahya</a></p>
        </div>
    </div>
</body>
</html>
