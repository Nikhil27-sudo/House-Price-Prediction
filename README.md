# House-Price-Prediction
## Problem Statement 

The objective is to develop a regression-based machine learning model that accurately predicts the value of residential properties. This house price prediction model serves as a valuable tool for sellers and buyers alike, enabling them to make well-informed decisions. For sellers, it provides guidance on setting an appropriate listing price, while for buyers, it aids in determining the fair value of a house.

## Exploratory Data Analysis

The data used for this project was obtained from a hackathon and consists of information on nearly ~30K houses located in various cities in India. Each house record contains 16 entries, including 15 input features and one output value. To ensure data quality, duplicates were checked and removed from the dataset. Additionally, any rows with missing values were deleted during the data-cleaning process. <br>

During the exploratory data analysis (EDA) phase, key attributes of the dataset were examined. These attributes include "POSTED_BY," which indicates the entity listing the property; "Area," representing the total square footage of the house; "Year_built," indicating the year of construction; "BHK_NO.," representing the number of rooms; "Furnishing," which specifies whether the property is furnished, unfurnished, or semi-furnished; and "RERA," indicating whether the property is approved by the Real Estate Regulatory Authority (RERA). These attributes will play a crucial role in building the machine learning model for accurately predicting house values.

Several data visualizations were conducted, including correlation heatmaps, scatter plots, and pie charts, to gain insights from the dataset. These visualizations helped identify relationships between variables, visualize the distribution of data points, and present categorical information in a clear manner. By visually exploring the data, patterns, trends, and potential outliers were examined, aiding in the understanding of the dataset's characteristics and assisting in feature selection for the machine learning model.
<br>
<br>   
<p align="center">
<img src="https://github.com/Nikhil27-sudo/House-Price-Prediction/blob/main/scatterplot.png" width="500" height="350">
</p>  
<p align="center">
<img src="https://github.com/Nikhil27-sudo/House-Price-Prediction/blob/main/piechart.png" width="800" height="150"> <br>
</p> 
<p align="center">
<img src="https://github.com/Nikhil27-sudo/House-Price-Prediction/blob/main/heatmap.png" width="380" height="380"> 
</p> 

## Models & Results

Regression algorithms, including Lasso, Ridge, ENet, Random Forest, and Gradient Boosting, were implemented in the project. 
These algorithms are used to deal with the problems like overfitting. 
Created Pipelines for each regression algorithm with different hyperparameters.
<br>
<br>
The performance evaluation of each model was carried out using various metrics, including the cross-validation (CV) score, R2_score, and 
mean absolute error (MAE). 
<br>
<br>
Among the models, the Gradient Boosting model achieved the highest CV score when predicting house prices. 
<br>
