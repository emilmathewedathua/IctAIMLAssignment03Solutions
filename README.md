# Car Price Prediction - Machine Learning Assignment

## About the Project

This project is part of my Artificial Intelligence and Machine Learning course assignment.
The objective of the project is to build a machine learning model that can predict the **price of a used car** based on different features such as year, kilometer driven, engine capacity, fuel type, transmission, and other specifications.

The project mainly focuses on understanding **data preprocessing, feature conversion, model training, and evaluation using Python**.


## Dataset

The dataset used in this project contains information about different used cars with features like:

* Make
* Model
* Price
* Year
* Kilometer
* Fuel Type
* Transmission
* Location
* Color
* Owner
* Seller Type
* Engine
* Max Power
* Max Torque
* Drivetrain
* Length
* Width
* Height
* Seating Capacity
* Fuel Tank Capacity

The **target variable** for prediction is **Price**.


## Steps Performed

### 1. Importing Libraries

Used libraries such as:

* pandas
* numpy
* matplotlib
* scikit-learn

### 2. Loading the Dataset

The dataset was loaded into a pandas dataframe for analysis.

### 3. Data Cleaning

Some preprocessing steps were required:

* Checking missing values
* Removing units like **cc, bhp, Nm**
* Converting columns into numeric format
* Filling missing values using mean or mode

### 4. Feature Encoding

Categorical columns such as **Fuel Type, Transmission, Seller Type, Owner** were converted into numerical form using **one-hot encoding**.

### 5. Train-Test Split

The dataset was divided into training and testing data using **train_test_split**.

### 6. Model Training

A **Linear Regression model** from scikit-learn was used to train the model.

### 7. Model Evaluation

The model was evaluated using:

* R² Score
* Mean Absolute Error (MAE)


## Results

R² Score: **0.6961**

Mean Absolute Error: **₹778,491**

The model gives a reasonable prediction but the accuracy can be improved by using more advanced models.


## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Google Colab


## Files in this Repository

car-price-prediction
│
├── car_price_prediction.ipynb
├── dataset.csv
└── README.md

## Note

This project was done as part of my **AI/ML course assignment** to understand the process of building a machine learning model for prediction problems.
