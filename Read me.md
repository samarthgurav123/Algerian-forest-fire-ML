Algerian Forest Fires Dataset

Data Set Information:

The dataset includes 244 instances that regroup a data of two regions of Algeria, namely the Bejaia region located in the northeast of Algeria and the Sidi Bel-abbes region located in the northwest of Algeria.

122 instances for each region.

The period from June 2012 to September 2012. The dataset includes 11 attribues and 1 output attribue (class) The 244 instances have been classified into fire(138 classes) and not fire (106 classes) classes.


Attribute Information:

1. Date: (DD/MM/YYYY) Day, month ('june' to 'september'), year (2012) Weather data observations

3. RH: Relative Humidity in %: 210 90

2. Temp: temperature noon (temperature max) in Celsius degrees: 22 to 42

4. Ws:Wind speed in km/h: 6 to 29

5. Rain: total day in mm: 0 to 16.8 FWI Components

6. Fine Fuel Moisture Code (FFMC) index from the FWI system: 28.6 to 92.5 7. Duff Moisture Code (DMC) index from the FWI system: 1.1 to 65.9

8. Drought Code (DC) index from the FWI system: 7 to 220.4

9. Initial Spread Index (ISI) index from the FWI system: 0 to 18.5

10. Buildup Index (BUI) index from the FWI system: 1.1 to 68

11. Fire Weather Index (FWI) Index: 0 to 31.1

12. Classes: two classes, namely Fire and not Fire

actions take:

1. Data cleaning 

Removing Null Values 
Removing spaces from  column names
Changed data Types
Dropping columns 
Encoding  obj column 


2. EDA

Classes column Pie-chat
Co-relation and Heatmap 
Box plot
Monthly fire column graph(columns: month and Classes)

3. Regression 
 
Dependent and Independent features
Train and test split 
Multi co-linearity 
Standardization 
Box plot before and after standardization
Linear Regression(mae,r2,scatter plot)
Lasso Regression(mae,r2,scatter plot)
Ridge Regression(mae,r2,scatter plot)
ElasticNet Regression(mae,r2,scatter plot)
