# Churn-Prediction-in-Telecom-Industry-using-Logistic-Regression

#### A Telecom company is losing Customers to its competitors. With the historical customer churn information that they have, they want a ML Model to predict, which of their present customers may churn. 

We have decided to create a `Logistic Regression` model to solve the problem. The Logistic Regression model will be expected to output a `Churn Probability` for every data under test. 

The input data is spread over 3 separate files - `churn_data.csv`, `cust_data.csv` and `internet_data.csv`. 

The Data includes the following: 

- `Personal Data (gender, children, whether senior citizen, dependents...)`
- `Services Related (Tenure with the provider, payment method, internet packs purchased, special offers...)`
- `Charges being incurred (Amount of recharge done per month...)`

## Exploratory Data Analysis (EDA)
The EDA process will comprise of Univariate and Multivariate Analysis alomg with abundant Visualisations.  

### Univariate Analysis
![image](https://github.com/dubey-adarsh/Churn-Prediction-in-Telecom-Industry-using-Logistic-Regression/assets/124420800/1abb87cf-2576-4a06-98a6-22564351b4c5)

#### Tenure
![image](https://github.com/dubey-adarsh/Churn-Prediction-in-Telecom-Industry-using-Logistic-Regression/assets/124420800/9ca6ffec-a3ed-45fb-a509-cc51fb7d15fe)

### Find for which kind of Contracts the churn probability is more
![image](https://github.com/dubey-adarsh/Churn-Prediction-in-Telecom-Industry-using-Logistic-Regression/assets/124420800/e1392c6e-3376-41bb-bb88-e7249c4f5c80)
![image](https://github.com/dubey-adarsh/Churn-Prediction-in-Telecom-Industry-using-Logistic-Regression/assets/124420800/9f3ecb62-8e1c-4d46-89ab-5c093684ea5d)
![image](https://github.com/dubey-adarsh/Churn-Prediction-in-Telecom-Industry-using-Logistic-Regression/assets/124420800/eb06f328-dc5b-43d9-ba3a-cf7e8221b8fe)

### Whether being on Monthly Charges is influencing Churn
![image](https://github.com/dubey-adarsh/Churn-Prediction-in-Telecom-Industry-using-Logistic-Regression/assets/124420800/608a4a97-8cb2-41e7-93cf-9919d619897d)

### Whether TotalCharges amount has influence on Churn
![image](https://github.com/dubey-adarsh/Churn-Prediction-in-Telecom-Industry-using-Logistic-Regression/assets/124420800/7e8b7235-17b2-47f8-9f25-6550da526a8f)

### Whether having Multiple Internet Connections have influence on Churn
![image](https://github.com/dubey-adarsh/Churn-Prediction-in-Telecom-Industry-using-Logistic-Regression/assets/124420800/9b20bebf-1eea-4798-9211-852c2b5dfdc9)
![image](https://github.com/dubey-adarsh/Churn-Prediction-in-Telecom-Industry-using-Logistic-Regression/assets/124420800/2b2144dd-5a7c-4063-a500-4e9c1da540a9)

### Whether type of Internet Service has influence on Churn
![image](https://github.com/dubey-adarsh/Churn-Prediction-in-Telecom-Industry-using-Logistic-Regression/assets/124420800/6b8d1c37-ffdb-4a99-9438-ff46ad93bee5)
![image](https://github.com/dubey-adarsh/Churn-Prediction-in-Telecom-Industry-using-Logistic-Regression/assets/124420800/2e901513-281b-4658-beb6-a528a5354fb1)
![image](https://github.com/dubey-adarsh/Churn-Prediction-in-Telecom-Industry-using-Logistic-Regression/assets/124420800/18c5c3b9-8790-4f35-93ab-39fbaad3f60d)



## Data Pre-processing

### Convert Binary Categorical Features (Yes/No) to 0/1

### Repeat the Correlation Matrix/Heatmap
![image](https://github.com/dubey-adarsh/Churn-Prediction-in-Telecom-Industry-using-Logistic-Regression/assets/124420800/4da40bfc-6066-4e4f-a70a-672fd78890fd)

