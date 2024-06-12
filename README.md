# Data Mining Mini Project 
In this project, we have taken **Nepal Weather Dataset** from [https://opendatanepal.com/dataset/district-wise-daily-climate-data-for-nepal/resource/39cd1c13-2051-4d4c-9ea3-ba8106833166](URL) 
and we try to analyze the weather data and weather trends over years. The data contains information from the year 1981 to 2019. There data shape is (88318, 22). There 22 columns are as follows: 
1. DATE: Collected monthly 
2. DISTRICT
3. LAT: Lattitude 
4. LON: Longitude
5. PRECTOT: MERRA2 1/2x1/2 Precipitation (mm day-1)
6. PS: MERRA2 1/2x1/2 Surface Pressure (kPa)
7. QV2M: MERRA2 1/2x1/2 Specific Humidity at 2 Meters (g/kg)
8. RH2M: MERRA2 1/2x1/2 Relative Humidity at 2 Meters (%)
9. T2M: MERRA2 1/2x1/2 Temperature at 2 Meters (C)
10. T2MWET: MERRA2 1/2x1/2 Wet Bulb Temperature at 2 Meters (C)
11. T2M_MAX: MERRA2 1/2x1/2 Maximum Temperature at 2 Meters (C)
12. T2M_MIN: MERRA2 1/2x1/2 Minimum Temperature at 2 Meters (C)
13. T2M_RANGE: MERRA2 1/2x1/2 Temperature Range at 2 Meters (C)
14. TS: MERRA2 1/2x1/2 Earth Skin Temperature (C)
15. WS10M: MERRA2 1/2x1/2 Wind Speed at 10 Meters (m/s)
16. WS10M_MAX: MERRA2 1/2x1/2 Maximum Wind Speed at 10 Meters (m/s)
17. WS10M_MIN: MERRA2 1/2x1/2 Minimum Wind Speed at 10 Meters (m/s)
18. WS10M_RANGE: MERRA2 1/2x1/2 Wind Speed Range at 10 Meters (m/s)
19. WS50M: MERRA2 1/2x1/2 Wind Speed at 50 Meters (m/s)
20. WS50M_MAX: MERRA2 1/2x1/2 Maximum Wind Speed at 50 Meters (m/s)
21. WS50M_MIN: MERRA2 1/2x1/2 Minimum Wind Speed at 50 Meters (m/s)
22. WS50M_RANGE: MERRA2 1/2x1/2 Wind Speed Range at 50 Meters (m/s) 

## Questions 
1. **How can we show the regions/district in Nepal that have extreme weather on a map?**
2. **Can we group district with similar weather conditions together?**
3. **How can we predict how much it will tempreture using other weather information like tempreture and humidity?** 

We have answered these questions on our notebook. There are also other visualizations that are helpful in understanding our data better. 
We have implemented Linear Regression, K-Means Clustering. Furthermore we have implemented LSTM for predicting **tempreture** over time. 
This project was really helpful because we implemented the things we learnt in our data mining class, also we tried something new,i.e implemented LSTM for time series forecasting. 

