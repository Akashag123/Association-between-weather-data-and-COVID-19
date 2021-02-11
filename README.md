# Association-between-weather-data-and-COVID-19
Here We will analyze collected Dataset With help of Machine Learning algorithems and Visualize in Different Mannner after that we will get some useful relation that will show the appropriate relationship among weather parameters and covid 19 spread and also we will compare this with mortality rate.

# Introduction and Background
Faced with the global pandemic of COVID-19, declared by World Health Organization (WHO) on March
11th 2020, and the need to better understand the seasonal behavior of the virus, I have conducted this
systematic review to describe current knowledge about the emergence and replicability of the virus and its
connection with different weather factors such as temperature and relative humidity.

The correlation between weather variables in the affected regions and the spread
of COVID-19 earned special attention in the upgoing research publications. Recently, researchers found
that a notable association between the weather variables (temperature and humidity) and the regions that
have major COVID-19 out Moreover,these regions are located at the same temperature zone in the
northern hemisphere.

Even though the pandemic is becoming a global issue, the most infected areas include
outbreak epicentres such as parts of Northeastern United States, China’s central province of Hubei, South
Korea, Japan, Iran, Italy, Spain, Germany, and England, all of which share an average temperature of 5 C
to 11 C and 47% to 79% humidity in January and February 2020. For Italy, regions with a temperature
higher than 15 degrees Celsius and 75% humidity have less spread of COVID-19 cases.

# Hypothesise and Methodology
• We hypothesise that the spread of the virus will decrease in the area with higher
temperature and humidity than areas with average records.

• Our work to find dataset which contains weather report ,location report and also
covid cases and death.

• Find the best predictive model for analyzing daily confirmed cases in countries
with the highest number of COVID-19 cases in the world.

• Predict the number of confirmed cases to have more readiness in healthcare
systems and make forecast using advanced machine learning algorithms.

• To validate the propose model, we have includes more number of weather and
climatic condition features that can influence the spread of the COVID-19 virus

# Data collection
1.https://www.kaggle.com/winterpierre91/covid19-global-weather-data

2.https://www.kaggle.com/imdevskp/coronavirus-report

# Methods
• In this work, we developed machine learning models used to investigate and understand the
real effect of temperature and humidity on the spread of COVID-19 .

• We have selected Decision tree as our predicting machine learning model.

• We are visualizing the data with help of scatter_geo which is visualizing the data on world
map and with help of lattitude and longitude.

• This algorithms were selected as they are the most widely used for predicting the spread of
COVID-19 and other prediction related analysis. This models was trained with the features
such as Population Density, Fertility Rate, Median Age, Infection Ratio, Urban Percentage,
Temperature, Humidity, Hours of Sunlight, and Wind Speed.

# Experimental results for virus infection (DecisionTreeRegressor)
• Feature ranking: Importance

• tempC, Importance: 0.2570790052197829

• sunHour, Importance: 0.25045373563517775

• humidity, Importance: 0.2058261530927998

• population, Importance: 0.13502776591200336

• windspeedKmph, Importance: 0.1296412831706275

• density, Importance: 0.015430137214657047

• age, Importance: 0.004753024036007128

• urban_percentage, Importance: 0.0014065283754076364

• fertility, Importance: 0.0003823673435367415
<img src=“https://github.com/KrisKasprzak/ILI9341_t3_controls 367”>

# Experimental results for Death (DecisionTreeRegressor)

• Feature ranking:

• tempC, Importance: 0.2783188108662247

• sunHour, Importance: 0.23116350589441223

• population, Importance: 0.2234751409533564

• 4, Feature: humidity, Importance: 0.12045105074320783

• 5, Feature: windspeedKmph, Importance: 0.10199897488467109

• 6, Feature: density, Importance: 0.024602767811378688

• 7, Feature: age, Importance: 0.01230138390568934

• 8, Feature: urban_percentage, Importance: 0.004100461301900208

• 9, Feature: fertility, Importance: 0.0035879036391593903

# Experimental results  for Death  (XGBRegressor)

Feature ranking:

1, Feature: tempC, Importance: 0.35495057702064514

2, Feature: age, Importance: 0.21332119405269623

3, Feature: population, Importance: 0.14023077487945557

4, Feature: humidity, Importance: 0.13851499557495117

5, Feature: sunHour, Importance: 0.0608714334666729

6, Feature: windspeedKmph, Importance: 0.05045246332883835

7, Feature: fertility, Importance: 0.030685920268297195

8, Feature: urban_percentage, Importance: 0.0058647445403039455

9, Feature: density, Importance: 0.005107935518026352

# Experimental results for virus infection (XGBRegressor)

Feature ranking:

1, Feature: tempC, Importance: 0.35495057702064514

2, Feature: age, Importance: 0.21332119405269623

3, Feature: population, Importance: 0.14023077487945557

4, Feature: humidity, Importance: 0.13851499557495117

5, Feature: sunHour, Importance: 0.0608714334666729

6, Feature: windspeedKmph, Importance: 0.05045246332883835

7, Feature: fertility, Importance: 0.030685920268297195

8, Feature: urban_percentage, Importance: 0.0058647445403039455

9, Feature: density, Importance: 0.005107935518026352

# THANK YOU
