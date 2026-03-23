Uber Fare Prediction - Machine Learning Project
This project aims to predict Uber fare prices based on various factors such as pickup/drop-off locations, timing, and passenger count. By leveraging historical trip data, we build a regression model to provide accurate fare estimates.
🚀 Project Overview
Goal:Predict the fare amount for Uber rides
.Dataset: Historical trip records including coordinates, timestamps, and fare amounts.
Target Variable: fare_amount
🛠️ Tech Stack
Language: Python
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Models Explored: Linear Regression, Random Forest, XGBoost (Adjust based on your actual work)
📊 Workflow
Data Cleaning: Handling missing values and removing outliers (e.g., negative fares).
Feature Engineering: Extracting hour, day, month, and year from timestamps; calculating Haversine distance from coordinates.
Exploratory Data Analysis (EDA): Visualizing price trends and correlations.
Model Training: Training multiple regression models.
Evaluation: Using metrics like RMSE (Root Mean Squared Error) and $R^2$ Score.
📈 Results
Current model performance:
RMSE: [Insert Value]
$R^2$ Score: [Insert Value]
⚙️ How to Run
Clone the repository:
Bash
git clone https://github.com/tharikar87aids-png/uber_project-ML.git
Install dependencies:
Bash
pip install -r requirements.txt
Run the notebook/script:
Bash
python main.py
