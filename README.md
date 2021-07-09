# p2-g3
FinTech Project 2

# Data
Data Pulled from following

Alpaca [Alpaca's Website](https://alpaca.markets/)

Newsapi [Newsapi's Website](https://newsapi.org//)

Nasdaq [Nasdaq's Website](https://www.nasdaq.com/)


# Data cleaning process
Pull in data through api, clean the data, dropped null, rename columns and read clean data to an output file.

# Analysis
## Auto Analysis
## Auto Result
    Yolanda area to fill out 
## Tech Analysis
* The first model in my analysis was predicated around the NEWSAPI and Google's Returns. I built this model by creating daily averages based on compound scores regarding specific headlines. This model used the headline "Advertising" due to Google's 80% of its revenue on its advertising business. Overall, the constraints from the NEWSAPI prove to be a road block in producing a accurate ML model. 
![NLP & GOOGLE](Google.png)

* The second model is an LSTM based model. It utilized S&P500's closing price to predict Apple's closing price. We did experiment with multiple window sizes but chose the 6 day window size. The model produced some level of accuracy between the months of February and March, but toward April we begin to see the divergence. This model could have been improved by utilizing a different feature instead of the S&P500 (A population set)
![Apple & S&P500](appleplot.png)
* The final model is based purely on COVID-19 related data. Specifically, I wanted to analyze how the vaccination process has been running as it factors into the conversation regarding the greater economy. This model proved to be the most dependable. 
![Vaccine Data](vaccine.png)
## Tech Result
* This project was a strong learning opportunity to further my understanding of both finance and machine learning. Overall, I would have liked to analyze covid specific data such as how covid cases had an impact on vaccine or health related stocks. 

## Finance Analysis
## Finance Result
    Biliksu area to fill out 

# Conclusion   
    Base on our analysis we can infer that 