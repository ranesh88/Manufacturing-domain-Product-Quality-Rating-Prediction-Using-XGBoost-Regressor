# Manufacturing-domain-Product-Quality-Rating-Prediction-Using-XGBoost-Regressor
Manufacturing is one of the main application of Data Science. It helps to optimize processes, predicts maintenance needs, and enhances product quality through advanced analytics and machine learning. It utilizes data to drive efficiency, quality, and innovation in production, supply chain management, and decision-making.

In this project, we implements the XGBoost Regressor for Quality Rating Prediction.

The objective of the project below mentioned ::

1. Predictive Maintenance
2. Quality Control
3. Supply Chain Optimization
4. Process Optimization
5. Demand Forecasting

This manufacturing dataset consists of the following columns:

1.	Temperature (°C): This column represents the temperature during the manufacturing process, 
#measured in degrees Celsius. Temperature plays a critical role in many manufacturing processes, 
influencing material properties and product quality.

2.	Pressure (kPa): The pressure applied during the manufacturing process, measured in kilopascals (kPa). 
#Pressure can affect the material transformation and the overall outcome of the manufacturing process.

3.	Temperature x Pressure: This feature is an interaction term between temperature and pressure,
#which captures the combined effect of these two process parameters.

4.	Material Fusion Metric: A derived metric calculated as the sum of the square of temperature and the cube of pressure.
It represents a material fusion-related measurement during the manufacturing process.

5.	Material Transformation Metric: Another derived metric calculated as the cube of temperature minus the square of pressure.
#It provides insight into material transformation dynamics.

6.	Quality Rating: The target variable, 'Quality Rating,' represents the overall quality rating of the produced items. 
#Quality is a crucial aspect of manufacturing, and this rating serves as a measure of the final product's quality.
