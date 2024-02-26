# Stock-Market-Analysis-And-Forecasting-Using-Deep-Learning

<img src="https://github.com/mohdumair8896/Stock-Market-Analysis-And-Forecasting/blob/master/Images/gg.jpg" width="550" height="350"/>

This is a project of Stock Market Analysis And Forecasting Using Deep Learning(pytorch,gru).

The task of stock prediction has always been a challenging problem for statistics experts and nance. The main reason behind this prediction is buying stocks that are likely to increase in price and then selling stocks that are probably to fall. Generally, there are two ways for stock market prediction. Fundamental analysis is one of them and relies on a company's technique and fundamental information like market position, expenses and annual growth rates. The second one is the technical analysis method, which concentrates on previous stock prices and values.

In this project, It analyze the data and then forecast the stock market.

DATASET
------
Google | Microsoft | IBM | Amazon

Analysis
------
<img src="https://github.com/mohdumair8896/Stock-Market-Analysis-And-Forecasting/blob/master/Images/download12.jpg" width="550" height="350"/>

As we can see here Microsoft's "High" value is very slowly increasing straight line. IBM's "High" value and Amazon's "High" value started from the approx same stage, even Amazon's "High" value was a bit lower but after 2012 Amazon's "High" value started to exponentially increase and slight drop for IBM's "High" value. Since 2016 there is a high fight going between Google's "High" value and Amazon's "High" value at 2018 Amazon's "High" value also beat Google's "High" value.

<img src="https://github.com/mohdumair8896/Stock-Market-Analysis-And-Forecasting/blob/master/Images/download13.jpg" width="550" height="350"/>

In Microsoft data, we can see in 2009 "High" value was under mean for a long time, so we can say there was some loss.

<img src="https://github.com/mohdumair8896/Stock-Market-Analysis-And-Forecasting/blob/master/Images/download14.jpg" width="550" height="350"/>

In Google data,there is a very slow increasing trend until 2012, but after 2012 there was an exponential high trend. And very high seasonality.

Forecasting 
------
**Time series forecasting** uses information regarding historical values and associated patterns to predict future activity. Most often, this relates to trend analysis, cyclical fluctuation analysis, and issues of seasonality. As with all forecasting methods, success is not guaranteed.

**GRU Model:**

Gated recurrent unit is essentially a simplified LSTM. It has the exact same role in the network. The main difference is in the number of gates and weights — GRU is somewhat simpler. It has 2 gates. Since it does not have an output gate, there is no control over the memory content. The update gate controls the information flow from the previous activation, and the addition of new information as well, while the reset gate is inserted into the candidate activation.

Results
-----
<img src="https://github.com/mohdumair8896/Stock-Market-Analysis-And-Forecasting/blob/master/Images/ibm.jpg" width="550" height="350"/>

<img src="https://github.com/mohdumair8896/Stock-Market-Analysis-And-Forecasting/blob/master/Images/ibm3.jpg" width="550" height="350"/>
-----