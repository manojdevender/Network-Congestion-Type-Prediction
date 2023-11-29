# Supervised-Learning-1
Domain
Telecom
Context
The telecom industry is faced by a challenge of network congestions due to various
factors. The ability to predict the correct type of network congestion can be of great
help in resolving the issue which led to the congestion. Predicting the type of
congestion is a real-life problem that needs to be solved in a more accurate and
automated way. Several factors determine the congestion type of a network like the
bytes consumed were due to video streaming, web browsing, cloud computing or
gaming amongst several others. Telecom companies apply numerous techniques for
analyzing and predicting network congestion type.

Approach
To solve this problem businesses collect data usage information of mobile phones from
various telecom companies and find out some relation between features of the mobile
phone service provider(eg:- bytes consumed through various services, etc.).
Here, the data collected is from various telecom firms. Target column has four types of
network congestion(including No Congestion). We will train a logistic regression
algorithm to build a model that can predict the type of network congestion.

Attribute Information
● cell_name : Unique identifier of the mobile cellular network
● 4G_rat: If 4G was provided or not (boolean)
par_year: year timestamp of data collection
● par_month: month timestamp of data collection
● par_day: day timestamp of data collection
● par_hour: hour timestamp of data collection
● par_min: minute timestamp of data collection
● subscriber_count: number of subscribers attached to the cellular network
● web_browsing_total_bytes: total number of bytes of data used for web browsing
● video_total_bytes: total number of bytes of data used for video streaming
● social_ntwrking_bytes: total number of bytes of data used for social networking
● cloud_computing_total_bytes: total number of byte of data used for cloud computing
● web_security_total_bytes: total number of bytes of data used for web security
● gaming_total_bytes: total number of bytes of data used for gaming
● health_total_bytes: total number of bytes of data used for health purposes
● communication_total_bytes: total number of bytes of data used for communication purpose
● file_sharing_total_bytes: total number of bytes of data used for file sharing
● remote_access_total_bytes: total number of bytes of data used for remote accessing data
● photo_sharing_total_bytes: total number of bytes of data used for photo sharing
● software_dwnld_total_bytes: total number of bytes of data used for downloading software
● marketplace_total_bytes: total number of bytes of data used for online marketplace
● storage_services_total_bytes: total number of bytes of data used for storage services
● audio_total_bytes: total number of bytes of data used for audio streaming services
● location_services_total_bytes: total number of bytes of data used for location related services
● presence_total_bytes: total number of bytes of data used for web presence
● advertisement_total_bytes: total number of bytes of data used for advertisement purposes
● system_total_bytes: total number of bytes of data used by system
● voip_total_bytes: total number of bytes of data used for voice over internet protocol services
● speedtest_total_bytes: total number of bytes of data used for speed testing services
● email_total_bytes: total number of bytes of data used for email purposes
● weather_total_bytes: total number of bytes of data used for weather related services
● media_total_bytes: total number of bytes of data used for media related services
● mms_total_bytes: total number of bytes of data used for multimedia messaging services
● others_total_bytes: total number of bytes of data used for all other purposes apart from the
ones mentioned in the previous columns
● beam_direction: Angle of direction of antenna beam
● cell_range: Cellular range strength of the network
● tilt: Antenna tilt
ran_vendor: Cellular phone vendor
● Congestion_Type: Type of network congestion (Target Variable). Please note NC means no
congestion.

Questions
1. You are given data of 78560 mobile phone data usage with the information of
features and you are supposed to analyze the data. Carry out exploratory data
analysis on the given dataset using different techniques
2. You are asked to build a logistic regression model to predict the network
congestion type. Implement logistic regression for the classification problem
using the appropriate techniques and also evaluate the performance of the
model
3. What all steps can be taken to improve the accuracy?
4. What do you conclude from this project?
5. Do you believe accuracy is a good metric for this model’s performance? What in
your opinion is a good metric to measure performance of a network congestion
prediction model.
Food for thought: Do you think logistic regression is the right algorithm for this
classification problem?

#Exploratory data analysis
#Logistic Regression
#Model performance for classifier
#Accuracy
