# weather-predictor
## Goals
This project should be able to use machine learning to predict the weather in Worcester based on the date or other factors. This will use scikit-learn to do such a task.

## Dataset
Below is where information about the dataset can be found. The data was originally acquired from [here](https://www.epa.gov/ceam/meteorological-data-massachusetts).

### Station Information
- Station WBAN Number: 94746
- Station Name: Worcester
- Station Location (State): MA
- Station Time Zone: +5(R)
- Station Latitude:  N   42 degrees 16 minutes
- Station Longitude: W   71 degrees 52 minutes
- Station elevation above sea level [meters]:  300
- File generation date: 2002-07-02 16:28:53
- Years present: 1961-1990

### Features
1. **date** refers to the date that the rest of the measurements in a row were taken. It is given in *mmddyy* format.   
2. **precipitation** refers to the amount of precipitation on a given date. It is measured in *cm/day*.
3. **pan_evap** refers to the [pan evaporation](https://en.wikipedia.org/wiki/Pan_evaporation) measurements of the station on a given date. It is measured in *cm/day*. 
4. **temperature** refers to the mean temperature on a a given date. It is measured in *degrees Centigrade* (an old-fashioned name for *Celcius*). 
5. **wind_speed** refers to the wind speed (using 10 meters for measurement) on a given day. It is measued in *cm/second*. 
6. **solar_rad** refers to the amount of [solar radiation](https://www.energy.gov/eere/solar/solar-radiation-basics#:~:text=Solar%20radiation%2C%20often%20called%20the,using%20a%20variety%20of%20technologies.) the station measured on a given day. 
7. **fao_sge** refers to [FAO Short Grass ETO](https://www.fao.org/land-water/databases-and-software/eto-calculator/en/) measurements in a given day.
