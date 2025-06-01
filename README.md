# Cab-Fare-Prediction
Cab rental services are expanding to a large extent, with the multiplier rate. The ease of using the  services and flexibility gives their customer a great experience with competitive prices. It is the need of  the hour to understand the importance of technology in such aspects.

This project builds a machine learning model to predict cab fares in New York City based on historical trip data. The goal is to provide accurate fare estimates using features such as pickup/dropoff locations, passenger count, and timestamp information.

1. Project Structure
   * Cab Fare Prediction.ipynb`: The core Jupyter Notebook containing EDA, feature engineering, model building, and evaluation.

2. Key Features
   * Exploratory Data Analysis (EDA) on spatial and temporal trip data
   * Feature engineering using geospatial calculations (Haversine distance)
   * Outlier removal and data cleaning
   * Model training using machine learning algorithms like XGBoost or Random Forest
   * Evaluation using RMSE (Root Mean Squared Error)

3. Dataset
   The data used is from a publicly available NYC taxi fare prediction dataset, including:
   * Pickup and dropoff datetime
   * Pickup and dropoff longitude & latitude
   * Number of passengers
   * Fare amount (target variable)

4. Technologies Used
   * Python
   * Pandas, NumPy
   * Scikit-learn
   * Matplotlib, Seaborn
   * XGBoost / RandomForest (for prediction)

5. Results
   * The model achieved an RMSE of approximately *\[insert RMSE from your notebook]* on the test set.
   * Visualizations show the correlation between distance, time of day, and fare.

