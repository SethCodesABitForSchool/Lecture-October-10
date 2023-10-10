# Lecture-October-10
Forecasting lecture. Lets say forecasting with an AR(1) but the true model is an Ar(4).
# Larger Models:
With larger model comes coefficient inefficinecy which is extrapolated into fute or forecast. 
- Consider 2 models:


  we obtain sequence of forecasts - FR1 anf FR1/FR2. The desireble is forecast errors with 0 mean and low variance.

Summary:

1. Larger Models and Coefficient Inefficiency: When dealing with larger models, such as AR(4) in comparison to AR(1), there can be challenges related to coefficient inefficiency.
2. Forecasting with Different Models: Consider two models: Model 1 (AR(1)) and Model 2 (AR(4)). Generate sequences of forecasts, denoted as FR1 and FR2, respectively.
3. Forecast Error Characteristics: The goal is to have forecast errors with a mean close to zero and low variance. Efficient forecasting models aim to minimize bias (mean forecast error) and variance of forecast errors.

Additional Considerations:
1. Model Selection:
Choosing the appropriate model involves a trade-off between model complexity and accuracy. Larger models may capture more complex patterns but could lead to overfitting.
2. Forecast Evaluation:
It's crucial to evaluate the performance of different models using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), or others depending on the context.
3. Overfitting:
Larger models may be prone to overfitting, capturing noise in the data rather than true underlying patterns. This can result in poor out-of-sample forecasting performance.
4. Model Validation:
Validate models using out-of-sample data to ensure that the selected model generalizes well to new data.
In the context of ARIMA models, including AR(p) models, selecting the appropriate order (p) involves considering model diagnostics, residual analysis, and goodness-of-fit measures.

# forecasting with ARMA model

He is talking something and i dont understand a thing. I need my pills. 
everythig sucks. conditional mean of the ar 1 process.
we need to construt the forecast errors for setting a confidence interval.
what is forecast error variance, if you only have one parameter then we are comparing one varinace ?
the value of the epsilon is something beta.
how do we construct the forecast error? - its in the slide i am very very hungry
# GC competetion
- one q forecast, 4q, 1 year and 4 years. upto 4 years 
- the effcts of the monetary policy takes about 12 mnths

# Mean square prediction error
- The MSPE - Mean square prediction error
- the goal is to pick the model with the small MSPE.
- the null hyp is equal forecasting accuracy, but if we reject the null - we have evidence to say that the mspe of something is greater than something then we take the smallest one.
- how are these people so smart, he has dobts ? wow just wow
- we have 2 sequences and we will be using them to forecast the error, i should have stayed at home.
# Case of contemporary correlated forecsat error - we consider some steps.
  1. granger newbolt - relax assumption 3
     Xi = E1i + E2i #small e
     Zi = E1i - E2i #small e
     p/roh(Xi, Zi) = E(XiZi) = p/roh1i^2 - p/roh2i^2

     if the correlation is positive, then we have the model one has the larger mean square foercast error.

  2. DieBolt and mariano - relax the other 3 assumptions
     - in that sense this model is a bit general
     - we are using the mean loss function 
     - d = 1/h SIGMA^H,i=1
  








