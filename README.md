# Wind Energy Prediction using Long Short Term Memory(LSTM)

For complete details please read CSE 523 Project Report.pdf.

# Introduction 

Wind speed/power has received increasing attention around the earth due to its renewable nature as well as environmental friendliness. With the global installed wind power capacity rapidly increasing, the wind industry is growing into a large-scale business. Reliable short-term wind speed forecasts play a practical and crucial role in wind energy conversion systems, such as the dynamic control of wind turbines and power system scheduling. A precise forecast needs to overcome problems of variable energy production caused by fluctuating weather conditions. Power generated by wind is highly dependent on the wind speed. Though it is highly non-linear, wind speed follows a certain pattern over a certain period of time. We exploit this time series pattern to gain useful information and use it for power prediction. LSTM is used to perform different experiments on the data and to form conclusion.

# Conclusion

We started with the aim of improving the predictions of power generated using wind energy and we have achieved that using LSTM as machine learning model and performing model optimization on it.

![alt text](https://github.com/ShashwatArghode/Wind-Energy-Prediction-using-LSTM/blob/master/Wind%20Prediction%20Result.JPG)

We have also observed that if the wind speed is less than 4 m/s the power generated by the system is zero. LSTM is not able to learn this pattern as this is not the part which it can understand in time series analysis. So, if a hybrid new model is created which can work as the combination of Decision Tree/Random Forest and LSTM we can improve upon these results as well.


