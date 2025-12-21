# Multiple-Linear-Regression

📊 Multiple Linear Regression – Tip Prediction App

An end-to-end Machine Learning web application built using Multiple Linear Regression to predict the Tip Amount based on Total Bill and Group Size.
The project demonstrates data preprocessing, feature scaling, model training, evaluation, visualization, and interactive deployment using Streamlit.

🚀 Project Overview

This project showcases how Multiple Linear Regression can be applied to real-world data by considering multiple independent variables.
Users can interactively enter values and instantly see the predicted tip amount.

📂 Dataset Information

Dataset: tips dataset (Seaborn)

Target Variable: tip

Input Features:

total_bill

size (group size)

🧠 Machine Learning Model

Algorithm: Multiple Linear Regression

Library: scikit-learn

Feature Scaling: StandardScaler

📐 Evaluation Metrics

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

RMSE (Root Mean Squared Error)

R² Score

Adjusted R² Score

🖥️ Application Features


🔹 Frontend

Built using Streamlit

Custom UI styled with CSS

Interactive sliders for:

Total Bill Amount

Group Size

Real-time tip prediction

🔹 Backend

Data preprocessing and scaling

Model training and inference

Prediction logic handled in Python

🔹 Visualization

Scatter plot of Total Bill vs Tip

Regression line plotted using Matplotlib

🌐 Live Deployment

🔗 Streamlit App

👉 https://multiple-linear-regression-hodta5bvnwzpp7qgpytpoz.streamlit.app/

🔗 GitHub Repository

👉 https://github.com/Nishath-1209/Multiple-Linear-Regression.git

📁 Project Structure
Multiple-Linear-Regression/
│
├── app_multiple_linear_regression.py   # Main Streamlit app
├── style.css                           # Custom CSS styling
├── requirements.txt                    # Project dependencies
├── README.md                           # Project documentation

🛠️ Tech Stack

Python

Streamlit

NumPy

Pandas

Seaborn

Matplotlib

Scikit-learn

⚙️ Installation & Local Execution

1️⃣ Install dependencies
```
pip install -r requirements.txt
```

2️⃣ Run the application
```

streamlit run app_multiple_linear_regression.py
```
📌 Key Learnings

Practical understanding of Multiple Linear Regression

Feature scaling using StandardScaler

Model evaluation using multiple metrics

Visualization of regression results

Deployment of ML models using Streamlit
