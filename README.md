# **Python API challenge - What's the Weather Like?**


![alt text](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.weathertap.com%2Fimages%2Fslide_global2.jpg&f=1&nofb=1)

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. So let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"


## Dependencies

>This was done in Jupyter Notebooks and you will need to install and import the following

matplotlib.pyplot

panda

numpy as np

requests

gmaps

os

json

seaborn 

scipy.stats

citipy

## Part I - WeatherPy

Your first requirement is to create a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude


![alt text](https://github.com/benwbarr/Python-API/blob/main/WeatherPy/Figures/LvC.png)
![alt text](https://github.com/benwbarr/Python-API/blob/main/WeatherPy/Figures/LvH.png)
![alt text](https://github.com/benwbarr/Python-API/blob/main/WeatherPy/Figures/LvT.png)
![alt text](https://github.com/benwbarr/Python-API/blob/main/WeatherPy/Figures/LvW.png)

Your second requirement is to run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitud

![alt text](https://github.com/benwbarr/Python-API/blob/main/WeatherPy/Figures/NMvL.png)
![alt text](https://github.com/benwbarr/Python-API/blob/main/WeatherPy/Figures/SMvL.png)
![alt text](https://github.com/benwbarr/Python-API/blob/main/WeatherPy/Figures/NHvL.png)
![alt text](https://github.com/benwbarr/Python-API/blob/main/WeatherPy/Figures/SHvL.png)
![alt text](https://github.com/benwbarr/Python-API/blob/main/WeatherPy/Figures/NCvL.png)
![alt text](https://github.com/benwbarr/Python-API/blob/main/WeatherPy/Figures/SCvL.png)
![alt text](https://github.com/benwbarr/Python-API/blob/main/WeatherPy/Figures/NWvL.png)
![alt text](https://github.com/benwbarr/Python-API/blob/main/WeatherPy/Figures/SWvL.png)


## Part II - VacationPy

Create a heat map that displays the humidity for every city from the part I of the homework.

![alt text](https://github.com/benwbarr/Python-API/blob/main/VacationPy/Figures/Capture.PNG)
