🔋 Machine Learning Based State of Charge (SOC) Prediction for Battery Management System

📌 Overview

This project focuses on estimating the State of Charge (SOC) of a lithium-ion battery using Machine Learning techniques. SOC represents the remaining battery capacity in percentage and is a critical parameter in Battery Management Systems (BMS) used in electric vehicles, renewable energy systems, and portable electronics.
Traditional SOC estimation methods such as Coulomb Counting and Open Circuit Voltage suffer from accumulated errors and limited accuracy. This project uses a data-driven ML approach to improve SOC prediction accuracy.
________________________________________
🎯 Objectives

•	Predict battery SOC using measurable parameters

•	Improve estimation accuracy using Machine Learning

•	Build a simple and efficient SOC prediction model for BMS applications
________________________________________
📊 Dataset

The dataset contains battery parameters such as:

•	Voltage

•	Current

•	Temperature

•	SOC (State of Charge)

The data is preprocessed and cleaned before training the model.
________________________________________
 Methodology

1.	Data collection and preprocessing
2.	Feature selection (Voltage, Current, Temperature)
3.	Train-test data split (80:20)
4.	Model training using Random Forest Regressor
5.	SOC prediction
6.	Model evaluation using MAE and R² score
________________________________________
 Machine Learning Model

•	Algorithm used: Random Forest Regression

•	Reason: Handles nonlinear battery behavior and gives high accuracy
________________________________________
📈 Results

The model predicts SOC with high accuracy and minimal error.

Performance is evaluated using:

•	Mean Absolute Error (MAE)

•	R² Score

•	Actual vs Predicted SOC graph

