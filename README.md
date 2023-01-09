# smart_beta_ml_prediction
This repository showcases my independent work, where I used standard feedforward and recurrent neural networks as well as gradient boosted decision tree algorithms to predict US equity returns. The input used for the predictions were statistically proven smart beta factors published by Brian Kelly in his academic paper "Is there a replication crisis" and smart beta factors published by Hou, Xue and Zhang in their paper "replicating anomalies". To furhter investigate differences between the prediction accuracy my work also included over 136 monthly macroeconomic factors published that were published by the FED. By comparing sophisticated machine learning algorithms to standard econometric models, my work identified key strengths of each prediction method. The US stock price predictions were then ultimately used to form long-short portfolios that were rebalanced monthly.  

My work is structured into seven parts: 

  1. US stock data collection (All publicly traded US stocks and the S&P 500 components)
  2. Smart Beta factor data collection and transformation
  3. US macroeconomic factor data collection and transformation
  4. Stock price prediction using simple econometric models such as LASSO or Elastic Net Regressions
  5. Stock price prediction using feedforward and recurrent neural networks as well as gradient boosted decision trees
  6. Long-short strategy portfolio formation and rebalancing 
  7. Data visualisation


