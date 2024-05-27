# SolarPanel-Tilt-Optimization
## **Optimal Solar Panel Angle Optimization Model**
- **Problem Statement:**
The efficiency of solar panels is highly dependent on their orientation concerning the sun. Finding the optimal angles for solar panel placement can significantly enhance energy capture and utilization.

- **Objective:**
The notebook aims to optimize solar panel performance using machine learning by integrating and preprocessing solar-related datasets, analyzing solar position and irradiance, exploring environmental factors, and implementing predictive models to predict key performance metrics. Through this analysis, it seeks to provide actionable insights for enhancing solar energy efficiency and sustainability.

- **Solution:**
The objective of this notebook is to provide a comprehensive analysis and optimization framework for solar panel performance using machine learning and deep learning techniques. The notebook aims to achieve the following goals:

- ###  **Key Components:**

 ####  **Data Loading and Preprocessing:** 
  - Import necessary libraries and load datasets related to `solar angles`, `solar forecasting`, and `historical weather data`.
  - Combine data from different sources for comprehensive analysis.
  - Explore and preprocess loaded datasets including handling missing values and converting columns to appropriate data types.
  
#### **Solar Position Analysis:**

- Calculate various solar position parameters such as zenith angle, azimuth, and elevation.
- Analyze the distribution and temporal patterns of solar position variables.
- Gain insights into seasonal patterns and atmospheric effects on solar position.
  
#### **Total Irradiance Calculation and Analysis:**

- Calculate total irradiance components like POA global, direct, diffuse, sky diffuse, and ground diffuse.
- Analyze seasonal variations and their impact on solar panel efficiency.
  
#### **Environmental Factor Analysis:**

- Analyze environmental factors such as humidity, temperature, wind speed, and surface albedo.
- Understand the typical ranges and distributions of environmental factors.
  
#### **Feature Importance and Model Implementation:**

- Perform feature importance analysis and model implementation using Random Forest Regressor and Gradient Boosting Regressor.
- Train models for target variables including POA Global Irradiance, Surface Tilt, and Surface Azimuth.
- Evaluate model performance using mean squared error (MSE) and R-squared (R2) scores.
  
#### **Deep Neural Network (LSTM) Model:**

- Implement a Long Short-Term Memory (LSTM) neural network for predictive modeling.
- Preprocess data, define the model architecture, and compile it with appropriate loss functions and optimizers.
- Monitor training and validation losses and mean absolute error (MAE).

#### **Output:**
- Merged dataset containing solar angles, weather conditions, and geographical location.
- Model performance metrics including `MSE`, `R2 scores`, and feature importance rankings.

#### **Dependencies:**

- Libraries such as pandas, numpy, pvlib, sklearn, plotly, tensorflow, keras for data manipulation and solar-related calculations.

#### **Insights:** 

- Over 20,000 entries in the merged dataset, providing significant data for analysis and model training.
- Comprehensive consideration of various parameters such as solar angles, environmental factors, and total irradiance for optimizing solar panel performance.

#### **Notebook Link:** 
- Please find the Google Colab link provided below for an in-depth exploration of our data analysis and corresponding graphs. To enhance your understanding, we've utilized Plotly for visualization, offering dynamic charts and plots.It's worth noting that these dynamic visualizations are not saved on GitHub, so the Colab environment is essential for accessing them effectively.
- [Tilt Angle Optimization and Suggestions Model](https://colab.research.google.com/github/KaifAhmad1/SolarPack-Assessment/blob/main/Solar_Panel_Tilt_Angle_Optimization_and_Suggestions.ipynb)


#### **Datasets Used:** 
- [National Solar Radiation Database(NSRDB) Solar Radiation and Meteorological Dataset](https://www.kaggle.com/datasets/ibrahimkiziloklu/solar-radiation-dataset)
- [Horizontal photovoltaic power output data for 12 sites in the Northern Hemisphere](https://www.kaggle.com/datasets/saurabhshahane/northern-hemisphere-horizontal-photovoltaic)




Author
Mohd Kaif


References 
- [Solar Panel Tilt Angle Optimization Using Machine Learning Model: A Case Study of Daegu City, South Korea](https://www.mdpi.com/1996-1073/13/3/529)
- [Optimal Photovoltaic Panel Direction and Tilt Angle Prediction Using Stacking Ensemble Learning](https://www.frontiersin.org/articles/10.3389/fenrg.2022.865413/full)
- [Development of Hybrid Model based on Artificial Intelligence for Maximizing Solar Energy Yield](https://www.researchgate.net/publication/376601883_Development_of_Hybrid_Model_based_on_Artificial_Intelligence_for_Maximizing_Solar_Energy_Yield)
- [Maximizing Annual Energy Yield in a Grid-Connected PV Solar Power Plant: Analysis of Seasonal Tilt Angle and Solar Tracking Strategies](https://www.mdpi.com/2071-1050/15/14/11053)
- [A Practical Approach for Estimating the Optimum Tilt Angle of a Photovoltaic Panel for a Long Period—Experimental Recorded Data](https://www.researchgate.net/publication/356494545_A_Practical_Approach_for_Estimating_the_Optimum_Tilt_Angle_of_a_Photovoltaic_Panel_for_a_Long_Period-Experimental_Recorded_Data)
- [World estimates of PV optimal tilt angles and ratios of sunlight incident upon tilted and tracked PV panels relative to horizontal panels](https://www.sciencedirect.com/science/article/abs/pii/S0038092X1830375X)
  
