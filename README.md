**BRITISH AIRWAYS DATA SCIENCE PROJECT**

British Airways (BA) is the flag carrier airline of the United Kingdom (UK). Every day, thousands of BA flights arrive to and depart from the UK, carrying customers across the world. Whether it’s for holidays, work or any other reason, the end-to-end process of scheduling, planning, boarding, fuelling, transporting, landing, and continuously running flights on time, efficiently and with top-class customer service is a huge task with many highly important responsibilities.

This project includes:
Customer Review Analysis and 
Customer Booking Prediction

**CUSTOMER REVIEW ANALYSIS**

Customers who book a flight with BA will experience many interaction points with the BA brand. Understanding a customer's feelings, needs, and feedback is crucial for any business, including BA. 
In this part of the project, the data which is the customers reviews was extracted from a website(Skytrax) using web scraping and Natural Language Processing(NLP) was used to generate insights from the customers' reviews. The NLP techniques used were Sentiment Analysis and Word Cloud.

1.**Sentiment Analysis**: Sentiment analysis is a technique used to determine the emotional tone or sentiment expressed in a text. It involves analyzing the words and phrases used in the text to identify the underlying sentiment, whether it is positive, negative, or neutral. Sentiment Analysis was used to unconver some insights from this data.
   
2.**Word Cloud**: Word Cloud is a data visualization technique used for representing text data in which the size of each word indicates its frequency or importance. This was used to retrieve the frequency of each word within the text and to know the key topic the customers were actively talking about.

**CUSTOMER BOOKING PREDICTION**

Customers are more empowered than ever because they have access to a wealth of information at their fingertips. This is one of the reasons the buying cycle is very different to what it used to be. Today, if you’re hoping that a customer purchases your flights or holidays as they come into the airport, you’ve already lost! Being reactive in this situation is not ideal; airlines must be proactive in order to acquire customers before they embark on their holiday. This project is focused on training a machine learning model to be able to predict the target outcome, which is a customer making a booking.

Firstly, exploratory data analysis was used to understand the data better, learn the different data characteristics, look out for useful pattern, null values and how the values of different variables were distributed. This is a very important first step in data analysis and data science. Feature Engineering was used in transforming the raw data into useful features for the machine learning model.

The Algorithm used in this project is Random Forest Classifier. 

**Random Forest Classifier** This is a supervised machine learning algorithm which is based on ensemble learning. This was used to train a machine learning model to predict the target output which is customer booking completed or not completed. This model was able to predict the target outcome with an accuracy 0f 0.8496 using 100 decision-trees. The algorithm also measured the features which are most predictive of the target variable. The performance of the model was evaluated using **Confusion Matrix** which gives us a summary of the correct and incorrect predictions broken down by each category. 

The model accurately predicted 85% of the target outcome, 83% of which were bookings not completed and 2% bookings completed.











