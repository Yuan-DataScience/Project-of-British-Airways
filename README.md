# British Airways Customer Booking Prediction

This project is a part of the Data Science virtual internship program offered by Forage with British Airways. British Airways (BA) is the flag carrier airline of the United Kingdom (UK). It operates thousands of flights daily, carrying customers across the world. Understanding customer feedback and predicting booking behavior is crucial for improving customer satisfaction and optimizing operations.

## Project Description

The virtual internship involves two main tasks:
- **TASK 1**: Web scraping to gain company insights
- **TASK 2**: Predicting customer buying behaviour

## TASK 1: Web Scraping to Gain Company Insights

### Results

The frequency chart below shows that the key topics within the reviews include “service”, “seat”, “crew” and “staff”, showing that people are actively talking about their experience and staff.

![Most Common Words in Reviews](https://github.com/Yuan-DataScience/Sales-Forecasting-Analysis-Project-British-Airways-/blob/main/Most%20Common%20Words%20in%20Reviews.png)

### Sentiment Analysis


Out of 1000 reviews, 546 were positive, 437 were negative and 17 were neutral. This means the majority of reviews were polarised as either positive or negative. The sentiment distribution chart below shows that the majority of the reviews are positive, with a significant portion being neutral, and a smaller portion being negative. This indicates that overall customer sentiment is relatively favorable.

![Sentiment Distribution of Customer Reviews](https://github.com/Yuan-DataScience/Sales-Forecasting-Analysis-Project-British-Airways-/blob/main/Sentiment%20Distribution%20of%20Customer%20Reviews.png)

## TASK 2: Predicting Customer Buying Behaviour

### Evaluation

- **1**: The most important variable in the model was purchase_lead, that is the time between purchase and departure.
- **2**: Information about the flight, e.g. flight time and duration was also significant, however booking origin of the customer was not important.
- **3**: The accuracy of the model was approximately 0.7 (Precision) and 0.003 (Recall), showing that this model requires more improvement. I suggest adding more customer-centric features into the model.
  
![Sales-Forecasting-Analysis](https://github.com/Yuan-DataScience/Sales-Forecasting-Analysis-Project-British-Airways-/blob/main/FeatureImportance.png)



## Skills Enhanced

- **Web Scraping**: Extracting data from the web.
- **Data Manipulation**: Cleaning and preparing data for analysis.
- **Data Visualization**: Creating insightful visualizations to present data.
- **Machine Learning**: Training and evaluating predictive models.
- **Data Science**: Applying analytical skills to make data-driven decisions.
- **Python Programming**: Using Python for data analysis and machine learning.

## Jupyter Notebook

The analysis and modeling were performed using Python and Jupyter Notebook. You can find the complete notebook [here](https://github.com/Yuan-DataScience/Sales-Forecasting-Analysis-Project-British-Airways-/blob/main/Python_SalesForecastingAnalysis.ipynb).

![Jupyter Notebook](https://github.com/Yuan-DataScience/Sales-Forecasting-Analysis-Project-British-Airways-/blob/main/Python_SalesForecastingAnalysis.ipynb)
