# eda_for_linear_regression
study_case_project_eda

# What is Exploratory Data Analysis?
1. A Step to understanding data dtructure
2. Identifying data errors
3. Choosing the right modeling technique
4. Generating data visualizations
5. Summarizing data

# What are the techniques commonly used for EDA?
Some of the commonly used techniques and tools in EDA include:
1. Descriptive Statistics: mean, median, mode, standard deviation, quartiles.
2. Data Visualization: histograms, scatter plots, box plots, and heatmaps.
3. Pattern and Anomaly Search: clustering, outlier detection, and trend analysis.

# When does EDA take place?
EDA is usually performed before more in-depth data analysis or statistical modeling to ensure that the analysis performed is valid and relevant to the data at hand.
By conducting a thorough EDA, we can ensure that further analysis is conducted with a solid foundation of understanding of the data, reduce the risk of errors, and improve the quality of analysis results.

# Introduction to The Dataset
This data is from kaggle. This dataset contains information about rice plants in Sumatra Island, Indonesia, while this dataset is presented in Indonesian language. The following are the 7 columns in the dataset 'Data_Tanaman_Padi_Sumatera':
1. Provinsi : Contains the names of Provinces in Sumatra
2. Tahun : Year of data recorded
3. Produksi : Production of rice in the each Province
4. Luas Panen : Harvested Area
5. Curah Hujan : Precipitation
6. Kelembapan : Humidity
7. Suhu rata-rata : Average Temperature
you can get this dataset >> (https://www.kaggle.com/datasets/ardikasatria/datasettanamanpadisumatera)

# The Objectives:
Understanding Data Structure
Identify Patterns and Trends
Explore the distribution of critical variables
Detect and deal with outliers or extreme values
Create data visualizations as a tool that makes understanding the data easier
Identify and handle data preprocessing tasks
Perform hypothesis testing to see relationships or patterns in the data
Supporting Decision Making
Effectively communicate results and insights from the EDA process

# Work Flow
1. reading dataset
2. view information
3. data preprocessing
4. descritive statistics
5. pivot table
6. standardization data
7. handling outliers
8. data visualizations for EDA
9. hypothesis testing & chi square test
10. visualizations for correlations data
11. build model linear regression
12. data evaluations
13. data visualizations for linear regression

# EDA Summary
Based on the linear regression model that has been performed on the 'Sumatra Rice Crops' dataset is as follows:
The predicted value of the target variable (Production) by the predictor variables (Harvested Area and Productivity)) is 
y = target variable
a = constant -> -0.000715
b1 = intercept of variable Harvested Area -> 0.824
b2 = intercept of Productivity variable -> 0.416
x1 = predictor variable of Harvested Area
x2 = predictor variable Productivity
The linear regression model that has been built has a fairly good performance, this is indicated by the MSE value of 0.01 and RMSE of 0.1. These two values illustrate the error rate of the model in predicting very low.
The regression model that has been built has a better ability to explain data variations, this can be seen from the R-Squared value obtained which is 98%. 

# Decision Making
Based on the results of the linear regression model that has been conducted on the 'Sumatra Rice Crops' dataset, the following are some suggestions that can be used for decision-making or policy-making:

Focus on the Harvested Area Variable:
Given that the coefficient of the Harvested Area variable (0.824) is larger than the coefficient of the Productivity variable (0.416), an increase in harvested area is likely to have a more significant impact on increasing production. Therefore, policies that encourage the expansion of agricultural land can be prioritized.

Increased Productivity:
Although the coefficient of productivity is smaller than that of harvested area, efforts to increase productivity per unit area remain important. This can be done through:
Application of more advanced agricultural technology.
Provision of training and counseling to farmers.
Use of superior seeds that are resistant to pests and diseases.

Agricultural Infrastructure Development:
Investments in infrastructure such as irrigation, farm roads, and crop storage facilities can help improve efficiency and reduce post-harvest losses, which in turn can increase production.

Continuous Monitoring and Evaluation:
Conduct continuous monitoring and evaluation of the policy implementation. Data collected from monitoring can be used to update regression models and adjust policies based on the latest results.

Collaboration with Researchers and Educational Institutions:
Establish collaboration with researchers and educational institutions for further research and development of relevant technologies in increasing rice production.

By implementing the above suggestions, it is expected that rice production in Sumatra can increase significantly, supporting food security and improving farmers' welfare.
