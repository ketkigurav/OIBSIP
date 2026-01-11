📘 Task 2 – Car Price Prediction

The objective of this project is to predict the selling price of a car
based on various features such as present price, mileage, fuel type,
seller type, transmission, and car age using machine learning regression
models.

🚗 Dataset
Dataset Used: Car Price Dataset

Features:
Present Price
Driven Kilometers
Car Age
Fuel Type
Seller Type
Transmission
Owner
Car Name

Target Variable:
Selling Price

The dataset contains historical car sale data and is used to demonstrate
regression techniques for predicting continuous values.

🛠️ Approach
The following steps were followed in this project:
Loaded and explored the car price dataset
Performed data cleaning and feature engineering
Converted categorical variables using one-hot encoding
Conducted Exploratory Data Analysis (EDA) to identify relationship
Split the dataset into training and testing sets
Trained a Linear Regression model as a baseline
Improved performance using a Random Forest Regressor
Evaluated models using R² score and Mean Absolute Error (MAE)
Compared model performance and selected the better-performing model

🤖 Machine Learning Models
Linear Regression (Baseline Model)
Random Forest Regressor (Improved Model)

Problem Type: Regression
Random Forest Regressor was used to capture non-linear relationships
between car features and selling price, resulting in more realistic and
accurate predictions.

📊 Results
Random Forest Regressor outperformed Linear Regression
Improved R² score and reduced prediction error (MAE)
More realistic car price predictions were obtained

Feature importance analysis highlighted key factors such as present
price, car age, and driven kilometers

🧠 Conclusion
The project demonstrates how machine learning regression techniques can be applied to predict car selling prices. The comparison between Linear
Regression and Random Forest models highlights the importance of choosing appropriate algorithms for complex real-world data. The Random Forest model provided better generalization and more reliable predictions.

🛠️ Tools & Technologies

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Google Colab

👩‍💻 Author
Ketki Gurav