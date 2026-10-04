# 🚗 Ford Car Price Prediction

A Machine Learning project that predicts the **selling price of Ford cars** based on various features such as model, year, mileage, engine size, transmission, fuel type, and other car-related attributes.

The project covers the complete Machine Learning workflow, from **data preprocessing and exploratory data analysis (EDA) to model training, evaluation, and price prediction**.

---

## 📌 Project Overview

Buying or selling a used car can make it difficult to determine the right price.

This project uses Machine Learning algorithms to learn patterns from historical Ford car data and predict the expected price of a car based on its features.

### 🎯 Objective

To build a Machine Learning model that can:

* Analyze historical Ford car data
* Identify important factors affecting car prices
* Train different Machine Learning models
* Compare model performance
* Predict the price of a Ford car

---

## 📊 Dataset

The project uses a **Ford Car Price Prediction dataset** containing information about Ford vehicles.

Typical features include:

* `model` – Ford car model
* `year` – Manufacturing year
* `price` – Car selling price
* `transmission` – Type of transmission
* `mileage` – Mileage of the car
* `fuelType` – Type of fuel
* `tax` – Vehicle tax
* `mpg` – Miles per gallon
* `engineSize` – Engine size

> The target variable is **`price`**, which represents the selling price of the car.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Exploratory Data Analysis
* **Scikit-learn** – Machine Learning
* **Jupyter Notebook**
* **Streamlit** – Web application/deployment (if included)

---

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Encoding Categorical Features
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Best Model Selection
   ↓
Car Price Prediction
```

---

## 🔍 Exploratory Data Analysis

The dataset was analyzed to understand:

* Distribution of car prices
* Relationship between mileage and price
* Effect of manufacturing year on price
* Effect of engine size on price
* Impact of fuel type
* Impact of transmission type
* Correlation between numerical features

Visualizations were created using **Matplotlib** and **Seaborn**.

---

## 🤖 Machine Learning Models

Different regression algorithms can be trained and compared, such as:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor

The model with the best evaluation performance can then be selected for final price prediction.

---

## 📈 Model Evaluation

The regression models are evaluated using metrics such as:

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted prices.

### Mean Squared Error (MSE)

Measures the average squared difference between actual and predicted prices.

### Root Mean Squared Error (RMSE)

Measures prediction error in the same unit as the target variable.

### R² Score

Shows how well the model explains the variation in car prices.

---

## 💡 Prediction

After training the final model, users can provide car details such as:

```text
Model
Year
Mileage
Transmission
Fuel Type
Tax
MPG
Engine Size
```

The Machine Learning model then predicts the estimated **Ford car price**.

---

## 🌐 Streamlit Application

If the Streamlit application is included, it provides a simple interface where users can enter the car details and receive a predicted price.

Run the application using:

```bash
streamlit run app.py
```

The application will open in your browser.

---


## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/shwetakadam45r/Ford_Car_Price_Prediction_ML.git
```

### 2. Navigate to the project

```bash
cd Ford-Car-Price-Prediction
```

### 3. Install required libraries

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
streamlit run app.py
```

---

## 📦 Requirements

Example `requirements.txt`:

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
streamlit
joblib
```

Use the versions from your actual environment if you want completely reproducible results.

---

## 🚀 Future Improvements

* Improve prediction accuracy
* Perform advanced feature engineering
* Try advanced ensemble models
* Add interactive visualizations
* Add more car brands and models
* Deploy the application online
* Add a car recommendation feature
* Improve the Streamlit UI

---

## 👩‍💻 Author

**Shweta Kadam**

Machine Learning / Python Project

---

## ⭐ If you found this project useful

Consider giving this repository a ⭐ on GitHub!
