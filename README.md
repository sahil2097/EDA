# EDA on Algerian Forest fire dataset

Data Information

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

Classes: two classes, namely fire and not fire


![eda](https://user-images.githubusercontent.com/108378037/194512806-1c0050cf-c609-4f04-acdb-f08710b08eca.PNG)

Report

Year has no variance.

Rain, DM, DC, ISI, BUI and FWI are right skewed

FFMC is left skewed


![image](https://user-images.githubusercontent.com/108378037/194513148-7040cce7-e1ce-4a8d-8433-4953a5598490.png)

Inference

maximum fire occurs in the month of july and aug.

Temperature highly impacts the fire

Maximum fire occures at humidity between 40-60

Rain inversely impacts the fire.

Increase in DMC, DC, ISI, BUI, FWI increase chances of fire.
