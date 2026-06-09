**State-Wise Solar Power Generation Forecasting Using Machine Learning**

**Overview**
This project focuses on forecasting state-wise solar power generation in India using advanced machine learning techniques. By leveraging historical solar generation records and meteorological data such as temperature, humidity, cloud cover, wind speed, pressure, UV index, and sun duration, the system predicts solar energy output with high accuracy.
The project compares multiple machine learning algorithms, including Linear Regression, Random Forest, Gradient Boosting, and XGBoost, to identify the most effective model for solar energy forecasting. Hyperparameter tuning techniques such as Grid Search were applied to optimize model performance and improve prediction reliability.

**Key Features**
State-wise solar power generation forecasting
Historical weather and solar generation data analysis
Data preprocessing and cleaning
Outlier detection and removal using IQR
Feature scaling using Min-Max Normalization
Comparison of multiple machine learning models
Hyperparameter tuning using GridSearchCV
Performance evaluation using MAE, MSE, RMSE, and R² Score
Future solar generation prediction using inference data
Dataset Features

**The dataset contains the following attributes:**
STATE
DATE
State_solar (Target Variable)
Temperature
Humidity
Precipitation
Pressure
Wind_Speed
Wind_Direction
Clouds
POP (Probability of Precipitation)
UVI (UV Index)
Sun_Duration

**Project Workflow**
Data Collection
Data Cleaning and Preprocessing
Exploratory Data Analysis (EDA)
Outlier Detection and Removal
Feature Scaling
Model Training
Hyperparameter Tuning
Model Evaluation
Forecast Generation
Final Model Selection

**Machine Learning Models Used**
Linear Regression
R² Score: 0.16
Baseline model for comparison

Random Forest Regressor
R² Score: 0.80
Captures non-linear relationships effectively

Gradient Boosting Regressor
R² Score: 0.92
Strong predictive performance

XGBoost Regressor
R² Score: 0.90
Advanced boosting algorithm with improved efficiency

Tuned Gradient Boosting
R² Score: 0.93
Optimized using GridSearchCV

Tuned XGBoost
R² Score: 0.95
Best-performing model

Selected for final deployment

**Model Performance Comparison**
Model	Accuracy (R²)
Linear Regression	16%
Random Forest	80%
Gradient Boosting	92%
XGBoost	90%
Tuned Gradient Boosting	93%
Tuned XGBoost	95%

**Technologies Used**
Python
Pandas
NumPy
Scikit-learn
XGBoost
Matplotlib
Seaborn
Jupyter Notebook

**Results**
The hyperparameter-tuned XGBoost model achieved the highest prediction accuracy with:
R² Score: 0.95
MAE: 3.27
MSE: 28.71

These results demonstrate the effectiveness of machine learning and ensemble boosting techniques in forecasting solar power generation and supporting data-driven renewable energy planning.

**Applications**
Renewable Energy Forecasting
Grid Stability Management
Energy Resource Planning
Government Policy Support
Smart Energy Systems
Sustainable Energy Development
Future Enhancements
Incorporate real-time weather APIs
Develop state-specific forecasting models
Deploy the model as a web application
Add deep learning models such as LSTM and GRU
Implement automated model retraining pipelines

**Conclusion**
This project demonstrates the successful application of machine learning for state-wise solar energy forecasting in India. Among all evaluated models, the hyperparameter-tuned XGBoost model provided the best predictive performance, making it a reliable solution for renewable energy forecasting and sustainable energy management.
