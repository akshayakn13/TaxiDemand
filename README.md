# About
Get the data from : http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml (2016 data).
The data used in the were collected and provided to the NYC Taxi and Limousine Commission (TLC)

# Information on taxis:
**Yellow Taxi:** Yellow Medallion Taxicabs
These are the famous NYC yellow taxis that provide transportation exclusively through street-hails. The number of taxicabs is limited
by a finite number of medallions issued by the TLC. You access this mode of transportation by standing in the street and hailing an
available taxi with your hand. The pickups are not pre-arranged.

**For Hire Vehicles (FHVs)**
FHV transportation is accessed by a pre-arrangement with a dispatcher or limo company. These FHVs are not permitted to pick up
passengers via street hails, as those rides are not considered pre-arranged.

**Green Taxi: Street Hail Livery (SHL)**
The SHL program will allow livery vehicle owners to license and outfit their vehicles with green borough taxi branding, meters, credit
card machines, and ultimately the right to accept street hails in addition to pre-arranged rides.

## Footnote:
In the given notebook we are considering only the yellow taxis for the time period between Jan - Mar 2015 & Jan - Mar 2016

# ML Problem Formulation
Time-series forecasting and Regression
To find number of pickups, given location coordinates(latitude and longitude) and time, in the query reigion and surrounding regions.
To solve the above we would be using data collected in Jan - Mar 2015 to predict the pickups in Jan - Mar 2016.

# Performance metrics
1. Mean Absolute percentage error.
2. Mean Squared error.

# Result
Trained two different models and their performance are as follows:
1. **Random Forest Regressor** - Test MAPE -0.0947
2. **XGBoost Regressor** - Test MAPE - 0.0974

# Credits
1. www.appliedai.com - for providing the resources
2. www.kaggle.com
3. https://grisha.org/blog/2016/02/16/triple-exponential-smoothing-forecasting-part-ii/
4. Goolge Colaboratory
5. NYC Taxi and Limousine Commission (TLC)

#### Any code related issues contact me on my id- akshayakn95@gmail.com
