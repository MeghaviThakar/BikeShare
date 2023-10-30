# BikeShare

This repository contains code for predicting bike sharing demand using linear regression. The code is written in Python and utilizes libraries such as NumPy, Pandas, Seaborn, Matplotlib, and Statsmodels. The goal of this project is to build a model that accurately predicts the demand for bike rentals based on various features such as temperature, humidity, wind speed, and date-related attributes.

•	Data Preprocessing
The code starts by loading a dataset containing bike sharing data.
It performs data preprocessing, which includes handling missing values and converting data types.
Categorical columns like 'season', 'mnth', 'weekday', and 'weathersit' are transformed into dummy variables for modelling.

• Data Visualization
The code uses to identify the outliners and coorelation if any in the data.
![image](https://github.com/MeghaviThakar/BikeShare/assets/126433977/95e0ac34-5d00-4a38-939b-9df705cf1d24)

•	Model Building
The code systematically builds and refines the linear regression model.
It starts with a simple model using only the 'temp' feature and progressively adds more features while evaluating model statistics.
Feature selection is performed based on p-values and VIF (Variance Inflation Factor) to ensure multicollinearity is addressed.
The final model provides insights into the predictors that most influence bike sharing demand.

![image](https://github.com/MeghaviThakar/BikeShare/assets/126433977/8e6f800a-71b4-4d16-9a52-62ff44e98c67)


•	Residual Analysis
Residual analysis is performed to assess the model's fit to the data.
Residuals are plotted to check for normal distribution and evaluate the accuracy of the model's predictions.

![image](https://github.com/MeghaviThakar/BikeShare/assets/126433977/fef276ea-ad18-41d7-baa6-479819dfb35b)

•	Making Predictions on the Test Set
The trained model is applied to a test dataset to make predictions on bike sharing demand.
The R-squared score is used to evaluate the model's performance on the test data.

•	Usage
Clone this repository to your local machine:
git clone https://github.com/your-username/bike-sharing-demand-prediction.git
Install the required Python libraries:
Copy code
pip install numpy pandas seaborn matplotlib statsmodels scikit-learn
Run the Jupyter Notebook or Python script to execute the code and explore the results.

Feel free to modify and expand upon this code to further enhance the predictive model or customize it for your specific use case.
