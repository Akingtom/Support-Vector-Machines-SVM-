🤖 Support Vector Machine (SVM) Classification for Social Network Ads

This project implements Support Vector Machine (SVM) classification to predict whether users will purchase a product based on their age and estimated salary from social network advertising data. 📊

📋 Dataset
The model uses the Social_Network_Ads.csv dataset containing:

🆔 User ID: Unique identifier for users

👥 Gender: User gender (Male/Female)

🎂 Age: User age

💰 EstimatedSalary: User's estimated salary

🛒 Purchased: Target variable (0 = No purchase, 1 = Purchase)

Dataset Shape: 400 samples × 5 features 📏

🎯 Features Used
The model uses two primary features for prediction:

🎂 Age: User's age
💰 EstimatedSalary: User's estimated annual salary

⚙️ Data Preprocessing

Feature Selection: Selected Age and EstimatedSalary as input features (X) and Purchased as target variable (y) 🎯

Train-Test Split: 75% training data (300 samples), 25% test data (100 samples) ✂️

Feature Scaling: Applied StandardScaler to normalize features for optimal SVM performance 📏
