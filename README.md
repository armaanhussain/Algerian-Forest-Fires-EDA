# Algerian-Forest-Fires-EDA

1.DATA COLLECTION AND UNDERSTANDING
I used a dataset on Algerian Forest Fires from UCI. The dataset contains a culmination of forest fire observations and data in two regions of Algeria: the Bejaia region and the Sidi Bel-Abbes region. The timeline of this dataset is from June 2012 to September 2012. In this project, we focused on whether certain weather features could predict forest fires in these regions using few Classification algorithms.

2. DATA EXPLORATION
In this step, we will apply Exploratory Data Analysis (EDA) to extract insights from the data set to know which features have contributed more in predicting Forest fire by performing Data Analysis using Pandas and Data visualization using Matplotlib & Seaborn. It is always a good practice to understand the data first and try to gather as many insights from it.
Below are tasks to be performed in EDA:

  1. Importing Libraries
  2. Data Cleaning for EDA Report
  3. Exploratory Data Analysis (EDA) on all Features


# Technologies Used


# Report

WEATHER SYSTEM REPORT

Temperature Highest Fire counts happened between 30-37 degree Celsius

Rain Highest Fire counts happened when there was no rain to very less rain ie. 0.0 to 0.3.

Wind Speed highest Fire count happened when the wind speed were between 13 to 19 Km/hr.

Relative Humidity highest fire count happened when the RH is between 50 to 80%.


FWI SYSTEM COMPONENTS REPORT

FWI (Canadian Forest Fire Weather Index)
Fine Fuel Moisture Code (FFMC) index which ranges between 28.6 to 92.5, here above 75 has higher chance of Forest fires.

Duff Moisture Code (DMC) index which ranges between 1.1 to 65.9, here 1.1-10 has lower chance of Forest fires whereas above 10-30 DMC has very high evidence of Forest fires in past.

Drought Code (DC) index which ranges between 7 to 220.4, here 0-25 is safe and has lower chance of Forest fires whereas range above 25 DC has higher chance of forest fires.

Initial Spread Index (ISI) index which ranges between 0 to 18, here 0-3 has lower Forest fires and above 3 ISI has higher chance of Forest fires.

Buildup Index (BUI) index which ranges between 1.1 to 68, here 1.1 to 10 has lower Forest fire chance and above 10 BUI has higher chance of forest fires.

Fire Weather Index (FWI) Index which ranges between 1 to 31.1, here 0-3 has lower chance of Forest fires and 3-25 FWI has higher chance of forest fires.



# Conclusion

Its observed that August and September had the most number of forest fires for both regions. And from the above plot of months, we can understand few things
Most of the fires happened in August and very high Fires happened in only 3 months - June, July and August. Less Fires were seen on September.
