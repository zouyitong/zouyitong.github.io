+++
title = "Projects"
+++

**Spring 2023: ORIE 5370 Optimization Modeling in Finance**<br />

Project Name:  <u>Long-Short trading strategy in Machine Learning </u> <br />

The objective of our project is to develop and implement a Long-Short trading strategy based on machine learning techniques and optimization methods. <br />

We will construct our portfolio based on ML selected ranking factors which have strong correlation with well-performed/bad-performed stocks to maximize expected returns and minimize risk. Our focus is on all the stocks in the Russell 3000 index, and we will consider a range of macro, fundamental, and risk factors as potential predictors of stock performance. To select the best ranking factors and stocks, we will use machine learning techniques such as PCA and K-means to analyze the correlation between factor exposures and returns of the previous time period . Based on these analyses, we will long the top 30 stocks and short the bottom 30 stocks to create a diversified portfolio. To ensure that our portfolio can adapt to the latest market, we will determine the rebalance period (i.e. daily, monthly, etc.) based on the performance of the strategy, and use optimization approach to decide the weights of these stocks. <br />

Overall, this project aims to provide a practical and data-driven approach to stock trading that leverages the power of machine learning and optimization methods to maximize returns and minimize risk.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Spring 2023: ORIE 5741 Learning with Big Messy Data**<br />

Project Name: <u>[Pairs Trading Strategy using Machine Learning Techniques](https://github.com/LinjiaF/ORIE_5741_MLStrategy.git) </u>  <br />

The main idea of pairs trading is to identify two highly correlated assets and make trading signals when a statistical anomaly is detected in the spread between the two assets. This is based on the belief that the two assets' prices, which have moved closely together in the past, will continue to do so consistently in the future.

In this project, we use the commodity ETFs data to find correlated pairs by employing Principle Component Analysis for dimensionality reduction and density-based clustering algorithm to find clusters. After pairs selecting, we use rolling regression with lookback window and Kalman Filter/Linear State Space Model to build trading models.

The project will help provide insight into the relations between various commodity ETFs and build appropriate trading strategies for them.


Back to [About Me]({{< ref "/About" >}})