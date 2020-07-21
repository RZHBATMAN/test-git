# Special libraries used for the project
## yfinance
This is the library supported by yahoo finance, where one can download historical data of stocks.
## from pykalman import KalmanFilter
pykalman is a library developed for implementing kalman filter algorithm, which is an algorithm that helps remove the noise from a wave (the stock price in my project).
## numpy.fft import fft,fftfreq,ifft
numpy.fft is used for conducting fourier transform. This is used in extracting the first feature for my classification problem. 
## sklearn
I use sklearn for pre-processing and conduct set split for convenience. 
## torch
This is the library required for building the neural network in my project. 
## statsmodels.api
This is the library I use to build the logistic regression in the model part and linear regression model in the back-testing part.

# Data resource
I retrieved all historical price using yfinance api mentioned above \\
Nasdaq Composite Index price is retrieved from https://finance.yahoo.com/quote/%5ENDX/history?period1=1527724800&period2=1590883200&interval=1d&filter=history&frequency=1d
