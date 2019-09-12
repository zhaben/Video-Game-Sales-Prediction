# Video-Game-Sales-Prediction
Linear Regression to predict video game sales in North America

The goal of this project is to predict the number of North American sales units for video games using known fields. The evaluation metric is the Mean Squared Error between the actual sales and the prediction.

I use OSEMN framework as a data science process to obtain, scrub, explore, model, and interpret the data.

After filtering data that posed problems for the linearity and normality standards for linear regeression, I use the forward selection model to choose which features were the best for predicting sales based on unknown data.

I finished with an MSE of .49, which indicates the absolute fit of the model, or how close the predicted values are to the actual data. 

MSE is the standard deviation of the prediction errors, or residuals. Residuals are a measure of how far the regression the data points are. RMSE shows how spread out the residuals are. The RMSE shows how concentrated the data is around the line of best fit.
