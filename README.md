Crazy Taxi IRL Proposal
Here is the website where the data is obtained: 
http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml
Github:
https://github.com/agentturbo1/Crazy-Taxi-IRL
Proposal specs:
	http://datasciencecourse.net/2018/project/
Basic info
Names:
	Lukas Gust
	Omar Hussain
UID’s:
	u0936790
	u0847356
	
E-mails:
	lukasgust31@gmail.com
	h.omar.mail@gmail.com
	
Background/Motivation
Taxis are a part of many New Yorker’s daily lives. We thought that it would be interesting to analyze data entries from NY taxis and find interesting relationships that may be lurking under the surface. There may be interesting inferences that can be made to make taxi user’s or taxi driver’s lives better. In addition to this, it can be useful to preemptively find where someone is travelling based only on their starting location and current conditions. Using predictive planning, routes can be chosen earlier to maximize efficiency and clear some traffic.
Project Objectives
The first objective of the project is to find correlations in the taxi data. These correlations can be used to make models, and the models can be used to predict outcomes, e.g. finding end location based on starting location, time, and date. Last, it must be asked if any of the correlations that are found are useful for the taxi industry. Regardless of this, the findings will be presented in an easy to understand manner. Find correlations between certain laws passed about drunk driving and see if there is an increase in taxi uses.

Data
Provided by the NYC Taxi & Limo Commission (TLC) from the following link:
http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml
This is from NYC’s government website. It is readily available and fairly neat from initial skimming.
More specific location data, such as businesses can be extracted from OpenStreetMap.org (OSM).
Data processing
Due to the neat nature of the data source there will be little data cleanup besides removing outliers and manipulating it to get the data that we want in order to do our analysis. We are likely to analyze several months worth of data to explore/infer some interesting relationships. We will be deriving trip duration from the given times of pickup and drop off. There are several different types of taxis in the NYC area. Yellow taxis: these are your usual yellow taxis that you see in the downtown Manhattan area. Green taxis: these are taxis that are purposely serve the outer regions of NY e.g. Staten Island, Brooklyn, Queens, and Upper Manhattan. Finally FHV (For-Hire-Vehicle): these are the rest of the taxi operations that operate under the TLC and are submitted to TLC by the operation. The data sets for these three are a little different and some manipulating will be needed in order to infer any interesting relationships based on type. We may have to acquire some empirical data based on physical research on certain locations that taxis are found at frequently e.g. businesses and area wealth. Searching for laws pertaining to driving under the influence and our given time intervals. 
Exploratory Data Analysis
Look at basic statistics for individual datasets see if we can identify any trends, if not combine them and check again. Find correlations of the variables to see if we can predict any results. Look at statistics from different types of taxis to see if there are similarities or differences. To do this we will use scatter plots and value counts to visually find relationships and then formalize them into the appropriate model. Find taxi ‘hotspots’. Frequencies of number of passengers. Count of trips on certain days or times of the day.
Methodology
Predictive planning will require machine learning, so using that to find accuracy with test data will allow us to gauge our models. In addition to this, regression tools can be used to find specific factors that may contribute to the results more than others, which can then be used to refine the model.
Schedule
Week 9: Finish homework 8 
Week 10: Spring break WOO! 🎉🎉🎉🎉
Week 11: Collect data 
Week 12: Identify correlations and make models
Week 13: Make predictions based on models - check results and refine
Week 14: Visualisation
Week 15: Make presentation and turn in

