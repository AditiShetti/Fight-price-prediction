# ✈️ Fight-price-prediction


## **Overview**  
The objective of this project was to predict flight prices based on various features such as airline, source and destination cities, class of service, duration,etc.  
An Excel dashboard was also made to showcase an overview of the dataset.  


<img src="https://github.com/user-attachments/assets/3a8c74c0-3350-4932-93a2-8938dea5658c" alt="plane image" width="95%" />


## **Model Used:**  
Random Forest : ***RandomForestRegressor*** from sklearn    

## **Dataset**   
This dataset is sourced from Kaggle.     
It has 300153 rows and 12 columns.  
  
🆔 **Unnamed**: 0: Index column.    
🛫 **airline**: Name of the airline.    
✈️ **flight**: Unique flight identifier or number.  
🌆 **source_city**: City where the flight originates.  
🕒 **departure_time**: Time of departure (morning, afternoon, evening, etc.).  
🛑 **stops**: Number of stops during the flight (non-stop, 1 stop, etc.).  
🕧 **arrival_time**: Time of arrival (morning, afternoon, evening, etc.).  
🏙️ **destination_city**: City where the flight lands.  
💺 **class**: Travel class (Economy, Business, etc.).  
⏳ **duration**: Total flight duration in hours and minutes.  
📅 **days_left**: Number of days left for the flight from the date of booking.  
💵 **price**: Ticket price in rupees.  


![Summary Flight price pred](https://github.com/user-attachments/assets/5fee6191-5bd9-4312-944b-f9d7c53fe953)

## **Excel dashboard for overview of dataset:**  
![Flight Price dashboard](https://github.com/user-attachments/assets/77a777b9-db9b-4738-aa1c-e653458b2c49)



## **Model Evaluation:**  
Model was evaluated using ***mean_absolute_error*** and ***r2_score*** from sklearn 

## **Model Performance:**  
r2_score : ***0.98***  
mean_absolute_error : ***1389.90***  
 
## **Tools Used**:    
**Pandas**: For data manipulation and analysis.  
**Numpy**: For data manipulation and analysis  
**Matplotlib**: For data visualisation  
**Seaborn**: For data visualisation    
**Sklearn**: For importing train_test_split and ML models  
**Excel**: To make a dashboard.  


**For any questions or feedback, feel free to reach out at Aditishetti9060@gmail.com😊**

