# Hourly Demand Prediction and Optimization Challenge

### Introduction

Welcome to the PHA Data Science Challenge! In this challenge, you will immerse yourself in a real-world scenario that combines the complexities of urban transportation with the unpredictability of weather patterns. Your mission is to predict the hourly demand for taxis in the Bronx area, leveraging a year’s worth of taxi trip data and hourly weather observations. Additionally, you will need to determine the optimal number of taxis required to efficiently meet this demand.

While the challenge is centered around urban transportation, the principles of demand forecasting you will employ are crucial across many industries, including healthcare staffing solutions. Accurately predicting and efficiently managing demand is at the heart of what we do at PHA, and we’re excited to see how you apply these skills in this context.

### Scenario

Imagine you are a data scientist working for a leading ride-hailing company. The company aims to optimize its operations by accurately forecasting demand in different regions of the city. One of the critical areas of focus is the Bronx, known for its dynamic and diverse neighborhoods. Accurate demand prediction in this area can significantly improve customer satisfaction and operational efficiency by ensuring that an adequate number of taxis are available when and where they are needed.

To tackle this challenge, you have been provided with historical trip data from taxis, combined with hourly weather data. Your task is to analyze this data, build predictive models, provide actionable insights, and determine the optimal number of taxis required to meet the predicted demand in the Bronx.

### Dataset Description

You will work with two primary datasets:

1. **Taxi Trip Data**: Historical data detailing individual taxi trips.
   - `tpep_pickup_datetime`: The date and time when the meter was engaged.
   - `tpep_dropoff_datetime`: The date and time when the meter was disengaged.
   - `passenger_count`: The number of passengers in the vehicle. This is a driver-entered value.
   - `trip_distance`: The elapsed trip distance in miles reported by the taximeter.
   - `PULocationID`: TLC Taxi Zone in which the taximeter was engaged.
   - `DOLocationID`: TLC Taxi Zone in which the taximeter was disengaged.

   *Corresponding zones can be found in the zone lookup table.*

2. **Weather Data**: Hourly weather observations corresponding to the same time period as the taxi trip data.
   - `temperature`: Air temperature in °C.
   - `precipitation`: Total precipitation (rain, showers, snow) sum of the preceding hour in mm.
   - `rain`: Only liquid precipitation of the preceding hour including local showers and rain from large-scale systems in mm.
   - `snowfall`: Snowfall amount of the preceding hour in cm.

### Task

Your objective is to predict the hourly demand for taxis in the Bronx area and determine the optimal number of taxis required to meet this demand. The task is divided into five parts, each progressively challenging to showcase your skills in data science, machine learning, and operational optimization.

1. **Baseline Model**:
   - Build a simple baseline model to predict hourly demand. Explain your choice of the baseline model and the performance metrics you use to evaluate it.

2. **Improved Model**:
   - Develop an improved model by incorporating additional features, refining your data preprocessing steps, or using more sophisticated algorithms. Compare its performance with the baseline model and explain the improvements. Discuss any feature engineering techniques or data transformation methods you employed.
    
3. **Best Model**:
   - Optimize your improved model to achieve the best possible performance. Explain the steps taken to enhance the model and the final results. Provide a clear comparison between the baseline, improved, and best models, highlighting the key improvements.

4. **Forecasting the First Week of September 2024**:
   - Using your best model, forecast the hourly demand for taxis in the Bronx for the first week of September 2024. Explain any additional steps or assumptions you took into consideration for this forecasting task, such as seasonal trends, external factors, or potential anomalies. 

5. **Optimal Number of Taxis**:
   - Determine the optimal number of taxis required to meet the predicted hourly demand in the Bronx. Make reasonable assumptions about factors such as average trip duration, taxi availability, and operational constraints. You might need to consider potential costs and benefits in your analysis. Explain your assumptions and the methodology used to calculate the optimal number of taxis. Discuss the implications of your findings on operational efficiency and customer satisfaction.

### Evaluation Criteria

Your submission will be evaluated based on the following criteria:

- **Coding Skills**: Clean, efficient, and well-documented code.
- **Problem-Solving Ability**: Logical approach to building and improving models.
- **Explanation and Justification**: Clear and concise explanation of the models, choices made, and the results.
- **Creativity and Innovation**: Original approaches to feature engineering, model optimization, and problem-solving.
- **Operational Insight**: Practicality and soundness of assumptions and methodology for determining the optimal number of taxis.

### Submission

Your submission should include:

1. **Code**: Python scripts or Jupyter notebooks with all the steps, explanations, and references.
2. **Report**: A detailed report explaining your approach, models built, performance comparison, and final results.
3. **Additional Files**: Any additional files required to reproduce your results.

Please submit your work either as a pull request on GitHub or as a single compressed file (ZIP) containing all the required components for reproducibility.
