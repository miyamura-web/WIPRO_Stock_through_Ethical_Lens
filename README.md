# WIPRO's Stock through Ethical 

## Problem Statement :- 
So the question is does ethical events affect a company's stock prices. Do you think that ethical or unethical events have an effect on stock movements ? Well with the help of a little bit of time series analysis and sentiment analysis I tried to figure it out. 

#### Data Set :- 
WIPRO's last 10 years stock data collected with the help of Yahoo Finance API, a library in python.

## Model :- 
![Screenshot 2025-04-30 120148](https://github.com/user-attachments/assets/eca708bb-1986-4ee0-ab9e-90fe04da15b8) 

Here this is the real time stock data of WIPRO company, which I plotted using yahoo finance API in python library, here I showed some ethical and unethical events of Wipro's. 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Analysis 1 (Time Series) :- 

### 1. Does unethical events affect stock price? 
![Screenshot 2025-04-30 120512](https://github.com/user-attachments/assets/f808c0b6-79c8-44fb-9325-6edeba862fdf)
#### Explanation :
Here in this plot I showed one unethical event of Wipro's, that is whistle blower complaint. It was about  unethical practices by a senior executive. So according the plot it may have a small impact, the stock is declining but one can said it was declining before that day, so is that mean unethical events does not affect stock price? 
#### Comparison - 
![Screenshot 2025-04-30 123354](https://github.com/user-attachments/assets/e38c980c-6a25-4015-a62a-8ced67996d76) 

Well a similar case happened with the Volkswagen company in the year 2015, here in the graph you can see that after this event their stock price declined by 33%. 
#### WIPRO's Step -
Well after the complaint Wipro disclosed it publicly with the statement "We received an anonymous whistle-blower complaint on November 15, 2019, which alleged certain unethical activities by a top executive." and they took necessary steps for it, they managed this situation well and ethically,  maybe that's why it did not affect that much.

#### Result -
Unethical events do affect stock prices, if it's not handled well internally and externally. But yeah one thing, it's not the only factor which affect stock prices, I just state may be unethical events can be a factor which affect stock prices.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

###  2. Does ethical events affect stock prices?
![Screenshot 2025-04-30 124023](https://github.com/user-attachments/assets/918a6908-4acb-4e06-990f-ee2c73ce556f)
####  Explanation : 
Well I plotted 3 ethical events of Wipro's, but after analysing this I did not find any correlation between ethical events and stock prices in a short period of time. But after seeing the last 10 years of data we can say that the company is still growing maybe cause they maintain ethics in their company. There's is a correlation between ethical events and long term growth.

#### Result - 
Ethics should not be an option, it should be compulsory for a company to have a gowth in a long term.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Analysis 2 (Sentiment Analysis) :- 
![Screenshot 2025-04-30 125133](https://github.com/user-attachments/assets/6f5fdd79-7c3b-4633-8704-df1d46f6cc86)

#### Explanation :
Each major event was assigned a sentiment score based on its textual description. Events such as whistle-blower complaints had negative value of 0.68 and compound value of  -0.296 it means individual scores comments are very negative but overall comments are still negative but slightly less harsh, means some peoples supports them.
And positive events like Ethical award recognition had the positive value of 0.872 and compound value of 0.7783 which means Ethical award recognition  events are seen as very positively both in immediate sentiment (0.872) and in the overall compound sentiment (0.7783).
Others are neutral it means Those events aren't causing strong emotional reactions — they’re just being reported or discussed neutrally.

#### Result - 
So the sentiment analysis revealed that while positive ethical events had mixed effects on stock prices, negative ethical events consistently triggered investor reactions and stock declines, emphasizing the market's sensitivity to corporate misconduct.


## Conclusion :- 
Ethical practices and transparency contribute to financial stability and investor confidence.
Ethics ≠ short-term profits ; Ethics =  long-term values. Unethical events can impact stock prices, especially if they are not handled well internally and externally. However, it is important to note that unethical events are just one of many factors that can influence stock price movements. 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



