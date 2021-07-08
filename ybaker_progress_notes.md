Yolanda Baker Progress notes
(some notes written by hand and transcribed here at a later date. I can't help that I'm old school.)



7/4/21 - Had a productive meeting with Bilikisu and Samuel. I think we've broken the wall of confusion and are now focused on building sentiment dataframes to create graphs.

7/4/21 - Spent most of last night and this morning attempting to get my code to accept the news API and Alpaca API. Did other work too. I played around with different scenarios, when I realized that I had both the newsapi and newsapi-python libraries installed. So I uninstalled both and reinstalled newsapi-python. At that point, things began working.

7/4/21 - Another setback. I didn't know how many requests I could make under the NewsApi. From the classwork example, it appeared 30 dates per request was acceptable, and so I kept the figure at 30. What I forgot to do was account for a fourth headline, not just three in the example. I went over my 100 item limit, and it appears I will have to wait at least 12 hours to begin the process again.
update: the API is working again. I will keep my request down to 5 for today. Once I get the hang of this part of the code, I will change it to 20.

7/4/21 - This was another difficult piece of code to complete. I couldn't figure out how to customize the "# Date and time under ISO formatting" so that I could enter specific dates.
I kept entering different dates, like "2021-07-04", under (datetime.now) area, and was receiving errors such as, "ValueError: unconverted data remains: T00:00:00-04:00"
However, I realized the "- timedelta(5)" was how I needed to customize the time. The 5 here represents how many days to go back. After I changed the timedelta from 30 to 5, things began working. 

7/5/21 - More progress today than any other. After newsApi access was allowed again this afternoon, I began pulling 13 days of data for my telsa_correlation section. I edited and completed the 3 and 6 days of correlation data. 
Completed the LSTM stock prediction section of the project, but it was not used as a ML model for NLP.

7/7/21 - wrapping things up. Things to remember:
LSTM networks are well-suited to classifying, processing and making predictions based on time series data, since there can be lags of unknown duration between important events in a time series.


