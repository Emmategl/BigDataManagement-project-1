# Big Data Management , MSc (Fall 2021)

Assignment 1: Data Pipelines

3.1 System requirements

For this assignment you should create the data preproccesing pipeline using sklearn in a system that:
- Reads the latest data from the InfluxDB
- Prepares the data for model training,including:
    - Aligning the time stamps of the two data sources (e.g.through resampling)
    - Handling missing data
    - Altering the wind direction to be a usable feature(by mapping to radians or encoding as categorical)
    - Scaling the data to be with in a set range
- Trains a linear regression model
- Uses the model to forecast wind power production

Much of the scaffolding for this is provided in template.py, so you primarily need to focus on the pipeline.

3.2 Hand-in
You should hand in a report describing your solution, including which design choices and trade-offs you made. Which steps does your pipeline include? What is the format of the data once it reaches the model? How could the pipeline/system be improved?
