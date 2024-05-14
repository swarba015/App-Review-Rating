# App-Review-Rating

# Overview
This project aims to predict app review ratings using various machine learning models. It involves text cleaning, feature engineering, model training, evaluation, and anomaly detection. Additionally, the project categorizes reviews by app type and performs sentiment analysis.

# Objective
The main objectives of this project are:

1. Predict the ratings of  app reviews based on the text of the reviews.
2. Detect anomalies in the predicted ratings.
3. Categorize app reviews into different types and sentiments.
4. Visualize the distribution of reviews by category and sentiment.

# Methodology
The project follows these steps:
1. **Data Loading:**
Load the App review dataset and inspect its structure.
2. **Text Preprocessing:**
Clean the review text by removing unnecessary characters, lemmatizing, and tokenizing.
3. **Feature Engineering:**
Transform the text data into TF-IDF features for model input.
4. **Model Development:**
Train and evaluate multiple regression models to predict review ratings. The models include Ridge Regression, Lasso Regression, Random Forest, and Gradient Boosting.
5. **Model Evaluation:**
Evaluate the performance of the models and choose the best one based on RMSE and MAE.
6. **Anomaly Detection:**
Detect anomalies in the predicted ratings compared to actual ratings.
7. **Visualization:**
Plot actual vs. predicted ratings and highlight anomalies.
8. **Export Data:**
Export the processed data to an Excel file.
9. **Categorize App Reviews:**
Categorize app reviews based on predefined keywords and perform sentiment analysis.
10. **Generate Word Cloud:**
Create a word cloud of the most frequent keywords in negative reviews.
11. **Categorize Negative Reviews:**
Further categorize negative reviews based on specific issues like crash, bug, update, etc.

# Findings
1. Ridge Regression outperformed other models with the lowest RMSE and MAE.
2. Anomaly detection identified reviews with significantly different predicted ratings compared to actual ratings.
3. Most reviews are categorized into 'other', followed by 'lifestyle' and 'feature' categories.
4. The sentiment analysis showed equal number of negative reviews to positive  reviews.

# How to Run the Project
To run this project on your local machine, follow these steps:

## Prerequisites
* Python 3.6 or higher
* Jupyter Notebook or any Python IDE
* Install necessary libraries
  
## Steps
Clone the Repository

## Load the Dataset ( Main Data set is not shared here):
Ensure you have the App review dataset in the same directory or update the path in the script.
## Run the Script:
Open the script in Jupyter Notebook or any Python IDE and run all the cells.
## View Results:
The processed data will be saved as review_processed_data.xlsx in the working directory.
  


   
