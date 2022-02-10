# Analyzing-Forest-Fire-Data

### Sofiane Ikkour


### **Context and Objective:**  
Forest fires can create ecological problems and endanger human lives and property. In this project we're aiming at understanding when they occur and what causes them to better know how to manage them. Our focus will not be directed towards a particular type of modeling, but rather we'll focus on visualizing it using different visualization methods. Hence, we'll perform exploratory data analysis to better understand the data and any relationships that might be present in it.

### **Dataset:**   
The data we'll be working with is associated with a [scientific research paper](http://www3.dsi.uminho.pt/pcortez/fires.pdf) on predicting the occurrence of forest fires in Portugal using modeling techniques. 

Here are the descriptions of the different variables in the dataset and the range of values for each variable taken from the paper:  
1. X: X-axis spatial coordinate within the Montesinho park map: 1 to 9.
2. Y: Y-axis spatial coordinate within the Montesinho park map: 2 to 9.
3. month: Month of the year: 'jan' to 'dec'.
4. day: Day of the week: 'mon' to 'sun'.
5. FFMC: Fine Fuel Moisture Code index from the FWI system: 18.7 to 96.2.
6. DMC: Duff Moisture Code index from the FWI system: 1.1 to 291.3.
7. DC: Drought Code Index from the FWI system: 7.9 to 860.6.
8. ISI: Initial Spread Index from the FWI system: 0.0 to 56.10.
9. temp: Temperature in Celcius degrees: 2.2 to 33.3.
10. RH: Relative humidity in percentage: 15.0 to 100.
11. wind: Wind speed in km/h: 0.4 to 9.4.
12. rain: Outside rain in mm/m2: 0.0 to 6.4.
13. area: The burned area of the forest(in ha): 0.00 to 1090.84.

The X and Y variables are coordinates of fire locations.
The acronym FWI stands for "fire weather index", a method used by scientists to measure risk factors for forest fires. This [link](https://cwfis.cfs.nrcan.gc.ca/background/summary/fwi) gives more details about the FWI and the variables included in our dataset.
