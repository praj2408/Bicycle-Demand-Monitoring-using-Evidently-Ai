# Bicycle-Demand-Monitoring-using-Evidently-Ai

## Introduction
Welcome to the Bicycle Demand Monitoring using Evidently AI project! This repository contains code and resources to help you analyze and monitor bicycle demand using Evidently AI.

Bicycle demand prediction is crucial for businesses and organizations involved in bike rental services, city planning, and transportation. Evidently AI allows us to create interpretable and actionable reports for our bicycle demand forecasting models, helping us make informed decisions.

## Project Overview
In this project, we will:

- Train a bicycle demand forecasting model.  
- Use Evidently AI to analyze and visualize model performance.  
- Monitor model performance over time.  
- Generate actionable insights from the analysis.  

## Prerequisites
Before you begin, ensure you have met the following requirements:

- Python 3.7+
- Jupyter Notebook (for running the provided notebooks)
- Evidently AI account (sign up at https://evidentlyai.com/)

## Data Description
You are provided hourly rental data spanning two years. For this competition, the training set is comprised of the first 19 days of each month, while the test set is the 20th to the end of the month. You must predict the total count of bikes rented during each hour covered by the test set, using only information available prior to the rental period.

## Data Fields
**datetime** - hourly date + timestamp    
**season** -  1 = spring, 2 = summer, 3 = fall, 4 = winter   
**holiday** - whether the day is considered a holiday  
**workingday** - whether the day is neither a weekend nor holiday  
**weather** - 1: Clear, Few clouds, Partly cloudy, Partly cloudy  
**2**: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist  
**3**: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds  
**4**: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog   
**temp** - temperature in Celsius  
**atemp** - "feels like" temperature in Celsius  
**humidity** - relative humidity  
**windspeed** - wind speed  
**casual** - number of non-registered user rentals initiated  
**registered** - number of registered user rentals initiated  
**count** - number of total rentals  


## Usage
Follow these steps to use this project:

Train your bicycle demand forecasting model (not provided in this repository). You can use any machine learning library or framework of your choice.  

Save the model and its predictions to a directory.  

Run the provided Jupyter notebooks in the notebooks directory to analyze the model performance using Evidently AI. Replace the sample data and model paths with your own.  

Use Evidently AI to monitor your model's performance over time. Set up a schedule for running the analysis to ensure continuous monitoring.  

Review the generated reports and actionable insights to make data-driven decisions regarding bicycle demand.  

## Contributing
If you would like to contribute to this project, please follow these guidelines:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and test them thoroughly.
- Create a pull request, explaining your changes and why they are necessary.

## License
This project is licensed under the MIT License.

Happy bicycling and demand monitoring! If you have any questions or need assistance, please feel free to reach out to us.
