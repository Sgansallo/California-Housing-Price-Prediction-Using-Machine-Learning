# California Housing Price Prediction (Machine Learning Project)

## Project Overview

This project uses the **California Housing Dataset** from Scikit-Learn to analyze housing data and build a machine learning model that predicts median house prices based on various features such as income, population, house age, and location.

The goal is to apply data science and regression techniques to understand patterns in housing prices and build a predictive model using Python.



##  Dataset

* Source: Scikit-Learn `fetch_california_housing`
* Rows: 20,640
* Features:

  * MedInc (Median Income)
  * HouseAge
  * AveRooms
  * AveBedrms
  * Population
  * AveOccup
  * Latitude
  * Longitude
* Target:

  * MedHouseVal (Median House Value)

## Objectives

* Perform Exploratory Data Analysis (EDA)
* Understand relationships between features
* Train a regression model
* Evaluate model performance
* Predict housing prices based on input features


##  Tools & Technologies

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Google Colab


## 📈 Workflow

1. Load dataset using Scikit-Learn
2. Perform data exploration (EDA)
3. Split data into training and testing sets
4. Train a regression model
5. Evaluate model performance
6. Make predictions


## 📊 Model Used

* Linear Regression (baseline model)


## 📉 Evaluation Metrics

* R² Score
* Mean Squared Error (MSE)


## How to Run This Project

1. Clone the repository
2. Open the notebook in Google Colab or Jupyter Notebook
3. Install required libraries:

   ```
   pip install -r requirements.txt
   ```
4. Run all cells step by step


##  Key Insights

* Median income has strong correlation with house prices
* Location (latitude & longitude) significantly affects pricing
* Simple regression models can provide a good baseline prediction


## 👨‍💻 Author

Samuel Gansallo
Data Science & Machine Learning Enthusiast


##  License

This project is for educational purposes.
