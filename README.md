# Fight-price-prediction
**✈️ Flight Price Prediction**


#**Overview**
The objective of this project was to predict flight prices based on various features such as airline, source and destination cities, class of service, duration,etc.  

https://www.google.com/url?sa=i&url=https%3A%2F%2Fclassroomclipart.com%2Fimage%2Fvector-clipart%2Fpassenger-plane-taking-off-from-the-city-skyline-59868.htm&psig=AOvVaw0eoxIQSaPUSfqjUCmu_AW8&ust=1731941433871000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCLj2-ebO44kDFQAAAAAdAAAAABAE

#**Model Used:**
Random Forest : RandomForestRegressor from sklearn  

#**Dataset** 
This dataset is sourced from Kaggle.   
It has 300153 rows and 12 columns.

🆔 Unnamed: 0: Index column.  
🛫 airline: Name of the airline.  
✈️ flight: Unique flight identifier or number.  
🌆 source_city: City where the flight originates.  
🕒 departure_time: Time of departure (morning, afternoon, evening, etc.).  
🛑 stops: Number of stops during the flight (non-stop, 1 stop, etc.).  
🕧 arrival_time: Time of arrival (morning, afternoon, evening, etc.).  
🏙️ destination_city: City where the flight lands.  
💺 class: Travel class (Economy, Business, etc.).  
⏳ duration: Total flight duration in hours and minutes.  
📅 days_left: Number of days left for the flight from the date of booking.  
💵 price: Ticket price in rupees.  

#**Model Evaluation:**
Model was evaluated using mean_absolute_error and r2_score from sklearn 

#**Model Performance:**
r2_score : 0.98
mean_absolute_error : 1389.90
 
#**Tools Used**:  
Pandas: For data manipulation and analysis.  
Numpy: For data manipulation and analysis  
Matplotlib: For data visualisation  
Seaborn: For data visualisation  
