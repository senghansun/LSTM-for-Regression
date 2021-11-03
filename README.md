# LSTM for Regression Tasks

### An LSTM Based Approach for LQ45 Financial Sector Indices Prediction

As one of the most popular financial market instruments, the stock has formed one of the most massive and complex financial markets in the world. It could handle millions of transactions within a short period of time and highly unpredictable. In this study, we aim to implement a famous Deep Learning method, namely the long short-term memory (LSTM) networks, for the stock price prediction. We limit the stocks to those that are included in the LQ45 financial sectors indices, i.e., BBCA, BBNI, BBRI, BBTN, BMRI, and BTPS. Rather than using too deep network architecture, we propose using a simple three-layer LSTM network architecture to predict the stocks’ closing prices. We found that the prediction results fall in the reasonable forecasting category. Moreover, it is worth noting that two of the considered stocks, namely, BBCA and BMRI, have the lowest MAPE values at 19.1020 and 18.6135, which fall in the good forecasting results. Hence, the proposed LSTM model is most recommended to be used on those two stocks.

This repository contains all the project codes, revision history, and data samples used in the project.
We welcome any comments, suggestions, and questions which can be addressed to the email provided below.

*RELATED ARTICLE*

For more detailed information related to the proposed method and previous studies, please refers to following publications and articles:
1. Hansun, S., Young, J.C. Predicting LQ45 financial sector indices using RNN-LSTM. J Big Data 8, 104 (2021). https://doi.org/10.1186/s40537-021-00495-x
2. Hansun, S., Suryadibrata, A. Gold Price Prediction in Covid-19 Era. International Journal of Computational Intelligence in Control 13(2) (2021). https://www.mukpublications.com/resources/ijcic%20v13-2-4.pdf
3. http://colah.github.io/posts/2015-08-Understanding-LSTMs/
4. https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21

*DATA SOURCE*
* The main data source is taken from *Yahoo! Finance* based on the Indonesia Stock Exchange (IDX) Major Evaluation Report. https://finance.yahoo.com/lookup
* For simplicity, the datasets being used can be found in the 'Dataset' folder

*ACKNOWLEDGMENTS*

We would like to acknowledge the contribution of many parties, especially for the public data source from *Yahoo! Finance*.

*CONTACT US*

*Email: seng.hansun@lecturer.umn.ac.id

*TERMS OF USE*

For publications that use codes and data provided in this repository, please cite:
* "Hansun, S. LSTM for Regression Tasks. https://github.com/senghansun/LSTM-for-Regression" 

and/or the published article:

* "Hansun, S., Young, J.C. Predicting LQ45 financial sector indices using RNN-LSTM. J Big Data 8, 104 (2021). https://doi.org/10.1186/s40537-021-00495-x"
