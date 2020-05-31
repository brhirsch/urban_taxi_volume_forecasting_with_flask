# urban_taxi_volume_forecasting_with_flask
A web app which visualizes historical and forecasted taxi ride volume in Chicago using an array of statistical forecasting models. 

The purpose of this project was to dive deeper into full stack development by incorporating the outputs of machine learning models into an application built on Python/Flask with a front end in html/bootstrap. 

![Network 1](https://github.com/brhirsch/urban_taxi_volume_forecasting_with_flask-/blob/master/images/taxi_ride_volume_forecast.png.PNG)


# TO DO
- Rework CSS to make it look nice (Need to research css frameworks like bootstrap)
- Define AWS and web architecture to host application. Save historical data in S3, use Lambda function to run forecasting models and save back in S3, have web app query S3 for forecast visuals
- Implement automatic forecast accuracy tracking (weekly calculation of forecast metrics)
- Create second part of web app which showcases weekly forecast accuracy for each method 

# Done
- Update function documentation 
- Add functionality to have a html radio button form which allows users to switch between visuals of forecasts made with Prophet, TBATS, and SARIMA
- Show past 2 weeks of historical data on same line chart as forecasts, with historical in blue and forecasts in orange 
