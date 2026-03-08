🏠 House Price Prediction using Linear Regression
📌 Project Overview

This project focuses on predicting house prices using Linear Regression, one of the most fundamental machine learning algorithms. The model analyzes different housing features such as area, number of bedrooms, bathrooms, parking availability, and furnishing status to estimate the price of a house.

This project was completed as part of the Oasis Infobyte Data Analytics Internship (OIBSIP).

🎯 Objective

The main objective of this project is to build a machine learning model that can predict house prices based on various housing attributes. This project also helps understand the relationship between different housing features and their impact on price.

📂 Dataset

The dataset used for this project is Housing.csv which contains information about houses and their respective prices.

Features included in the dataset:

Area

Bedrooms

Bathrooms

Stories

Main Road Access

Guest Room

Basement

Hot Water Heating

Air Conditioning

Parking

Preferred Area

Furnishing Status

Price (Target Variable)

🛠️ Tools and Technologies Used

Python

Google Colab

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

⚙️ Project Workflow
1. Data Collection

The housing dataset was loaded using the Pandas library.

2. Data Preprocessing

Categorical values such as yes/no were converted into numerical values so they could be used in the machine learning model.

3. Feature Selection

All columns except price were used as input features for predicting house prices.

4. Train-Test Split

The dataset was divided into training data (80%) and testing data (20%).

5. Model Training

A Linear Regression model was trained using the training dataset.

6. Prediction

The trained model was used to predict house prices from the testing dataset.

7. Model Evaluation

The model performance was evaluated using metrics such as Mean Squared Error (MSE) and R² Score.

📊 Visualization

A scatter plot was used to compare actual house prices and predicted house prices, helping to understand how accurately the model performs.

📁 Repository Structure

OIBSIP_DataAnalytics_Task6
│
├── Housing.csv
├── House_Price_Prediction.ipynb
├── Project_Report.pdf
└── README.md

👨‍💻 Author

Narayan
Data Analytics Intern – Oasis Infobyte
