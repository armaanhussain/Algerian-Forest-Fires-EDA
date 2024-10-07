# Algerian-Forest-Fires-EDA

![image](https://github.com/user-attachments/assets/074f83a5-88f5-48f0-bbbe-9560f3e2896f)



1.Data Set Information:

The dataset includes 244 instances that regroup a data of two regions of Algeria,namely the Bejaia region located in the northeast of Algeria and the Sidi Bel-abbes region located in the northwest of Algeria.
122 instances for each region.
The period from June 2012 to September 2012. The dataset includes 11 attribues and 1 output attribue (class) The 244 instances have been classified into fire(138 classes) and not fire (106 classes) classes.

Attribute Information:

Date : (DD/MM/YYYY) Day, month ('june' to 'september'), year (2012) Weather data observations

Temp : temperature noon (temperature max) in Celsius degrees: 22 to 42

RH : Relative Humidity in %: 21 to 90

Ws :Wind speed in km/h: 6 to 29

Rain: total day in mm: 0 to 16.8 FWI Components

Fine Fuel Moisture Code (FFMC) index from the FWI system: 28.6 to 92.5

Duff Moisture Code (DMC) index from the FWI system: 1.1 to 65.9

Drought Code (DC) index from the FWI system: 7 to 220.4

Initial Spread Index (ISI) index from the FWI system: 0 to 18.5

Buildup Index (BUI) index from the FWI system: 1.1 to 68

Fire Weather Index (FWI) Index: 0 to 31.1

Classes: two classes, namely Fire and not Fire



2.DATA COLLECTION AND UNDERSTANDING
I used a dataset on Algerian Forest Fires from UCI. The dataset contains a culmination of forest fire observations and data in two regions of Algeria: the Bejaia region and the Sidi Bel-Abbes region. The timeline of this dataset is from June 2012 to September 2012. In this project, we focused on whether certain weather features could predict forest fires in these regions using few Classification algorithms.


3.DATA EXPLORATION
In this step, we will apply Exploratory Data Analysis (EDA) to extract insights from the data set to know which features have contributed more in predicting Forest fire by performing Data Analysis using Pandas and Data visualization using Matplotlib & Seaborn. It is always a good practice to understand the data first and try to gather as many insights from it.
Below are tasks to be performed in EDA:

        1. Importing Libraries
        2. Data Cleaning for EDA Report
        3. Exploratory Data Analysis (EDA) on all Features



# Technologies Used


![image](https://github.com/user-attachments/assets/2e036652-242b-449a-b977-3f4f1f775376)            ![image](https://github.com/user-attachments/assets/4b14b0ce-dd02-4d07-81a6-7c8d47729e22)

![image](https://github.com/user-attachments/assets/733d117d-f615-4dbf-ac6a-548e8519e6da)            ![image](https://github.com/user-attachments/assets/d5fffb9b-6a62-4475-807e-e425cdae2c54)



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
