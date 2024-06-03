# British Airways Customer Booking Prediction

## Project Description

This project involves predictive modeling and analysis of British Airways customer bookings using machine learning techniques. The goal is to predict whether customers will make a booking based on various features in the dataset. The project also includes scraping and analyzing customer reviews to uncover insights. 

During this programme, participants step into the shoes of a British Airways team member, completing tasks that replicate the work of BA's Data Science team. The skills practiced include web scraping, data manipulation, data visualization, and building predictive models using Python.

## Table of Contents
- [Project Description](#project-description)
- [Background](#background)
- [Skills Enhanced](#skills-enhanced)
- [Data Exploration and Preparation](#data-exploration-and-preparation)
- [Feature Engineering](#feature-engineering)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Feature Importance Visualization](#feature-importance-visualization)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Background

British Airways (BA) is the flag carrier airline of the United Kingdom (UK). It operates thousands of flights daily, carrying customers across the world. Understanding customer feedback and predicting booking behavior is crucial for improving customer satisfaction and optimizing operations.

The project tasks include:
1. **Scraping and collecting customer feedback** from the Skytrax website.
2. **Cleaning and analyzing the data** to extract insights using techniques like topic modeling, sentiment analysis, and wordclouds.
3. **Building a predictive model** to forecast customer booking behavior using the provided dataset.
4. **Evaluating the model** and presenting the findings using visualizations and metrics.

## Skills Enhanced

- **Web Scraping**: Extracting data from the web.
- **Data Manipulation**: Cleaning and preparing data for analysis.
- **Data Visualization**: Creating insightful visualizations to present data.
- **Machine Learning**: Training and evaluating predictive models.
- **Data Science**: Applying analytical skills to make data-driven decisions.
- **Python Programming**: Using Python for data analysis and machine learning.

## Data Exploration and Preparation

### Data Loading

```python
import pandas as pd

# Load the dataset
file_path = 'F:/Jobs/Certificates/British_Airways/Data/customer_booking_300.csv'
df = pd.read_csv(file_path)

# Display the first few rows and columns
print(df.head())
print(df.columns)
