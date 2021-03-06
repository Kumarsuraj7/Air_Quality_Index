# Air Quality Index

__Data Fetch__
- https://en.tutiempo.net/climate website for the year 2013 to 2018
- HTML pages are stored for 12 months coresponding to each year in 2013-2018
- Python code to acomplish this task: Html_script.py

__Cleaning the HTML data__
- HTML data are further stored in the real_year.csv files
- Data cleansing is performed before storing the data
- All the year data is combined into the real_combine.csv 

__EDA__
- Expolatory Data analysis performed on the available data

![image](https://user-images.githubusercontent.com/23438020/155111459-2ab0cc08-ac63-402d-b85e-ad52b169e116.png)

__Model Selection__
- Different Regression models are fitted on the data like Linear regression, Decision Tree Regressor, Random Forest Regressor and XGBoost Regressor.
- Hyper parameter tunning is applied to best tune the parameters.
- Selected the Random Forest Regressor as it is giving the best RMSE value among the other ML models. 

__Deployement__
- Deployed the model on local server using Flask
