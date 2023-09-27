# Bike-Sharing-Demand-Prediction-Capstone-Project

![github](https://github.com/anasmalik081/Bike-Sharing-Demand-Prediction-Capstone-Project/assets/84465546/4fe4936d-6f41-406c-ad75-424df80d440b)

### Project tile - Seoul Bike Sharing Demand Prediction
### Description:
This is a supervised ML (regression) capstone project on bike sharing demand prediction given by [Alma Better](https://www.almabetter.com/).

![github](https://github.com/anasmalik081/Bike-Sharing-Demand-Prediction-Capstone-Project/assets/84465546/4fe4936d-6f41-406c-ad75-424df80d440b)

### Problem statement:
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

![download](https://github.com/anasmalik081/Bike-Sharing-Demand-Prediction-Capstone-Project/assets/84465546/e4af98d5-c76a-41fa-b735-ae4f94357f10)

![github](https://github.com/anasmalik081/Bike-Sharing-Demand-Prediction-Capstone-Project/assets/84465546/4fe4936d-6f41-406c-ad75-424df80d440b)

### Note: Dataset is provided by the company, Alma Better.

### Dataset description:
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

Attribute Information:

* Date : year-month-day
* Rented Bike count - Count of bikes rented at each hour
* Hour - Hour of he day
* Temperature-Temperature in Celsius
* Humidity - %
* Windspeed - m/s
* Visibility - 10m
* Dew point temperature - Celsius
* Solar radiation - MJ/m2
* Rainfall - mm
* Snowfall - cm
* Seasons - Winter, Spring, Summer, Autumn
* Holiday - Holiday/No holiday
* Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

![github](https://github.com/anasmalik081/Bike-Sharing-Demand-Prediction-Capstone-Project/assets/84465546/4fe4936d-6f41-406c-ad75-424df80d440b)

### Project Flowchart:

1. Initial preparations(Loading the dependencies and the data)

2. Data Inspection

3. Data Wrangling
     * Handling null values
     * Handling duplicate values
     * Removing Outliers
    
4. Exploratory Data Analysis (EDA)
   
5. Feature Engineering
     * Feature encoding
     * Checking correlation for feature removal
     * Removing Multicollinearity
     * Obtaining correlation between dependent and independent variables
       
6. Pre processing of the data
     * Target feature conditioning
     * Creating train and test dataset
     * Feature Scaling
       
7. Model implementation
     * Linear Regression
     * Lasso Regression(L1 Regularization)
     * Ridge Regression(L2 Regularization)
     * ElasticNet Regression (L1 + L2 Regularization)
     * Random Forest Regression
       
8. Cross Validation and Hyperparameter Tuning

![github](https://github.com/anasmalik081/Bike-Sharing-Demand-Prediction-Capstone-Project/assets/84465546/4fe4936d-6f41-406c-ad75-424df80d440b)

### Conclusion:

1. EDA insights:
    * The number of renting bikes increases as summer season starts.
    * The number of renting bikes decreses as winter season starts.
    * In summer, 37% people prefer to rent a bike and in winters, only 7.9% people prefer to rent a bike.
    * Most number of people prefer to rent a bike when the temperature of the day is in between 15 degree to 30 degree celcius.
    * When humidity percentage is in between 30 to 70, people prefer to rent a bike.
    * Most of the bikes are rented when sky is shiny or there is no rainfall or snowfall.
    * Majority of the bikes are rented on a functioning day. On holiday majority of people prefer to stay home.
    * When there is a functioning day, most of the bikes are rented during daytime. The peak hour of renting bike is 6 PM evening. The second highest peak hour of renting a bike is 8 AM morning.
    * The lowest number of bikes are rented around 4 AM and 5 AM.

2. Results from ML models:
    * Random Forest algorithm gave the best performance among all of the models with R2 Score of 0.98.
    * The Linear and Ridge regression both shows the 77% accuracy on training dataset. On test dataset, Linear Regression shows 77% accuracy and Ridge Regression shows 78% accuracy.
    * The Lasso and ElasticNet Regression both shows 76% accuracy on training dataset and 78% accuracy on test dataset.
    * After doing cross validation on Lasso, Ridge and ElasticNet regression, the accuracy for all of them remain same on test dataset. This shows no overfitting.

3. Challenges faced:
    * Removing Outliers.
    * Encoding the categorical columns.
    * Removing Multicollinearity from the dataset.

![github](https://github.com/anasmalik081/Bike-Sharing-Demand-Prediction-Capstone-Project/assets/84465546/4fe4936d-6f41-406c-ad75-424df80d440b)

**For further information you can check the google colab file added in the repository.**

**If you find any mistakes or have any suggestions for me, please reach out to me, all the criticism is heartly welcomed.**

**You can also reach out to me for project collaborations.**

**My Email Id - anasmalik081@gmail.com**

**My LinkedIn profile - [Profile](https://www.linkedin.com/in/anas-malik-01/)**

### Thankyou for tagging along to the end.
