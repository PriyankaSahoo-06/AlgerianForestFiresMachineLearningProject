# 🔥 AlgerianForestFiresMachineLearningProject

## 📌 Project Overview
This project predicts the **Fire Weather Index (FWI)** using Machine Learning techniques on the Algerian Forest Fire Dataset.
The objective is to analyze weather and environmental conditions and estimate the Fire Weather Index, which helps in understanding the potential risk of forest fires.
The trained Machine Learning model has been integrated with a Flask web application that allows users to enter environmental parameters and obtain FWI predictions through a simple web interface.

## 🎯 Problem Statement
Forest fires are a major environmental concern and can lead to significant ecological and economic damage.
The goal of this project is to predict the Fire Weather Index (FWI) using meteorological and fire-related measurements such as temperature, humidity, rainfall, wind speed, and other fire indices.

## 📊 Dataset Information
**Dataset:** Algerian Forest Fires Dataset

### Features Used
* Temperature
* Relative Humidity (RH)
* Wind Speed (Ws)
* Rain
* FFMC
* DMC
* ISI
* Classes
* Region

### Target Variable
* FWI (Fire Weather Index)

## 🛠 Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Flask
* HTML
* CSS
* Git
* GitHub

## 📈 Project Workflow
### 1. Data Cleaning
* Removed unnecessary rows
* Fixed column names
* Converted datatypes
* Handled categorical variables
### 2. Exploratory Data Analysis (EDA)
* Distribution Analysis
* Correlation Analysis
* Heatmaps
* Count Plots
* Box Plots
### 3. Feature Engineering
* Region Encoding
* Class Encoding
* Feature Selection
### 4. Model Training
The following regression models were explored:
* Linear Regression
* Ridge Regression
* Lasso Regression
* Elastic Net Regression
### Final Model Selected
**LassoCV**
Reason:
* Better generalization
* Automatic feature selection
* Reduced overfitting

## 📊 Model Evaluation
Evaluation Metrics Used:
* Mean Absolute Error (MAE)
* R² Score
The final model demonstrated good predictive performance on unseen test data.

## 💾 Model Persistence
The trained model and scaler were saved using Pickle.
Files:
* `lassocv.pkl`
* `scaler.pkl`

## 🌐 Flask Web Application
The project includes a Flask-based web application where users can:
* Enter environmental parameters
* Submit data through a form
* Predict Fire Weather Index (FWI)
* View prediction results instantly

## 📂 Project Structure
AlgerianForestFiresMachineLearningProject/
│
├── application.py
├── templates/
│ ├── index.html
│ └── home.html
│
├── models/
│ ├── lassocv.pkl
│ └── scaler.pkl
│
├── Algerian_forest_fires_dataset_UPDATE.csv
├── Algerian_forest_fires_dataset_cleaned.csv
├── algerian_forest_project.ipynb
├── README.md
├── requirements.txt
└── .gitignore

## 🚀 How to Run the Project
### Clone Repository
git clone https://github.com/PriyankaSahoo-06/AlgerianForestFiresMachineLearningProject.git

### Install Dependencies
pip install -r requirements.txt

### Run Flask Application
python application.py

### Open Browser
http://127.0.0.1:5000

## 📷 Project Screenshots
### Home Page
AFFP-1
### Prediction Page
AFFP-2
### Prediction Result
AFFP-3

## 📚 Key Learning Outcomes
Through this project, I learned:
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Regression Algorithms
* Model Evaluation
* Feature Scaling
* Model Serialization using Pickle
* Flask Web Development
* Git and GitHub Workflow

## 👩‍💻 Author
**Priyanka Sahoo**
Data Analytics & Machine Learning Enthusiast
GitHub: https://github.com/PriyankaSahoo-06
