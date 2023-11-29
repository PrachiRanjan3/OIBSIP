# **Car Price Prediction with Machine Learning**

![Task-3](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/Task-3.png)

# **Features -> Year, Present_Price, Driven_kms, Fuel_Type, Selling_type, Transmission, Owner**
# **Target ->  Selling_Price**

# **Cleaned dataset**

![cleaned_dataset](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/cleaned_data.csv)

# **Feature vs No_of_cars**

### No of cars for each Car_Name

![No of cars for each Car_Name](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/No%20of%20cars%20for%20each%20Car_Name.png)

### No of cars for each Year

![No of cars for each Year](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/No%20of%20cars%20for%20each%20Year.png)

### No of cars for each Fuel_Type

![No of cars for each Fuel_Type](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/No%20of%20cars%20for%20each%20Fuel_Type.png)

### No of cars for Selling_type

![No of cars for each Selling_type](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/No%20of%20cars%20for%20each%20Selling_type.png)

### No of cars for Transmission type

![No of cars for each Transmission](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/No%20of%20cars%20for%20each%20Transmission.png)

### No of cars for Owner type

![No of cars for each Owner](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/No%20of%20cars%20for%20each%20Owner.png)

# **Multi-Variate Analysis**

![Multi-Variate Analysis](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/Multi-Variate%20Analysis.png)

# **Bi-variate Analysis**

### Selling Price vs Year

![Bi-variate Analysis Selling_Price](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/Bi-variate%20Analysis%20Selling_Price.png)

### Present Price vs Year

![Bi-variate Analysis Present_Price](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/Bi-variate%20Analysis%20Present_Price.png)

# **Data Transformation**

[transformed_data.csv](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/transformed_data.csv)

# **Relationship between Features**

### Year vs Selling_Price

![scatter plot Year vs Selling_Price](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/scatter%20plot%20Year%20vs%20Selling_Price.png)

### Year vs Present_Price

![scatter plot Year vs Present_Price](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/scatter%20plot%20Year%20vs%20Present_Price.png)

### Year vs Driven_kms

![scatter plot Year vs Driven_kms](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/scatter%20plot%20Year%20vs%20Driven_kms.png)

### Correlation

[correlation.csv](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/correlation.csv)

![Correlation](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/Correlation.png)

#### From the above correlation plot we can infer the following :-
#### A -> Selling_Price is influenced by :
#### (i) Present_price by a score of 0.88
#### (ii) Fuel_Type by a score of 0.5
#### (iii) Selling_type by a score of 0.55
#### (iv) Transmission_type by a score of 0.35
#### B -> Present_Price is influenced by :
#### (i) Selling_price by a score of 0.88
#### (ii) Fuel_Type by a score of 0.43
#### (iii) Selling_type by a score of 0.51
#### (iv) Transmission_type by a score of 0.33

# **Histogram Distribution**

### Distribution of Selling_Price

![Distribution of Selling_Price](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/Distribution%20of%20Selling_Price.png)

### Distribution of Present_Price

![Distribution of Present_Price](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/Distribution%20of%20Present_Price.png)

### Distribution of Driven_kms

![Distribution of Driven_kms](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/Distribution%20of%20Driven_kms.png)

# Training the data using Machine Learning Model

### Linear Regression
### R2 score : 0.78

![Actual vs  Predicted Selling Prices using Linear Regression](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/Actual%20vs.%20Predicted%20Selling%20Prices%20using%20Linear%20Regression.png)

### Random Forest Regression
### R2 score : 0.98

![Actual vs Predicted Selling Prices using Random Forest Regression](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/Actual%20vs%20Predicted%20Selling%20Prices%20using%20Random%20Forest%20Regression.png)

### XGBoost Regressor
### R2 score : 0.99

![Actual vs Predicted Selling Prices by XGBoost Regression](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/Actual%20vs%20Predicted%20Selling%20Prices%20by%20XGBoost%20Regression.png)

### Important Features

![Top 10 Features having impact on the selling price of the car using XGBoost Regression](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/Top%2010%20Features%20having%20impact%20on%20the%20selling%20price%20of%20the%20car%20using%20XGBoost%20Regression.png)

## predicted dataset

[predicted_data.csv…](https://github.com/PrachiRanjan3/OIBSIP/blob/main/Task-3%20Car%20Price%20Prediction%20with%20Machine%20Learning/predicted_data.csv)
















