**BRITISH AIRWAYS DATA SCIENCE PROJECT**

British Airways (BA) is the flag carrier airline of the United Kingdom (UK). Every day, thousands of BA flights arrive to and depart from the UK, carrying customers across the world. Whether it’s for holidays, work or any other reason, the end-to-end process of scheduling, planning, boarding, fuelling, transporting, landing, and continuously running flights on time, efficiently and with top-class customer service is a huge task with many highly important responsibilities.

This project includes:
Customer Review Analysis and 
Customer Booking Prediction


**CUSTOMER REVIEW ANALYSIS**

For any business, understanding customer sentiment and feedback is essential. In this segment of the project, I extracted customer reviews from the Skytrax website using web scraping. Leveraging Natural Language Processing (NLP), I harnessed the power of sentiment analysis and word clouds to gain valuable insights from these reviews.

1.**Sentiment Analysis**: Sentiment analysis involves assessing the emotional tone expressed in text. It involves analyzing the words and phrases used in the text to identify the underlying sentiment, whether it is positive, negative, or neutral. Sentiment Analysis was used to unconver some insights from this data.
   
2.**Word Cloud**: Word Cloud is a data visualization technique used for representing text data in which the size of each word indicates its frequency or importance. This was used to retrieve the frequency of each word within the text and to know the key topic the customers were actively talking about.

**CUSTOMER BOOKING PREDICTION**

Customers are more empowered than ever because they have access to a wealth of information at their fingertips. This is one of the reasons the buying cycle is very different to what it used to be. Today, if you’re hoping that a customer purchases your flights as they come into the airport, you’ve already lost! Being reactive in this situation is not ideal; airlines must be proactive in order to acquire customers before they embark on their holiday. This project is focused on training a machine learning model to be able to predict the target outcome, which is a customer making a booking.

Firstly, **Exploratory Data Analysis** was used to understand the data better. This step unveiled data characteristics, patterns, null values, and the distribution of variables. It served as a crucial initial phase in the data analysis process.

**Feature Engineering** transformed raw data into meaningful features for our machine learning model, enhancing predictive accuracy. 

**Machine Learning Model: Random Forest Classifier** The algorithm of choice for this project was the Random Forest Classifier, a supervised machine learning method based on ensemble learning. This algorithm was trained to predict the likelihood of a customer completing a booking.

The model exhibited an accuracy of 0.896 using 100 decision trees. Additionally, it identified the most influential features for predicting booking outcomes through **feature importance analysis**. 

**Model Evaluation: Confusion Matrix** To assess model performance, we employed a confusion matrix, providing a breakdown of correct and incorrect predictions in each category. The model accurately predicted 85% of the target outcomes, with 83% of these predictions pertaining to incomplete bookings and 2% to completed bookings.

This project embodies a comprehensive analysis of customer reviews and a robust machine learning approach to predict customer bookings, equipping British Airways with valuable insights and tools to enhance customer service and operational efficiency.











