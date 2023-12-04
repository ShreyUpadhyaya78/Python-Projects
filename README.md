# Python-Projects
This repository contains script to get weather information from openweathermap api. A free version of api is used to get the weather data in json format. 

There are two scripts: weather_module.py and test_weather_app.py. 

## weather_module.py
weather_module.py is the main script which outputs two kinds of information:
* Get general weather info at current time of any major city in the world
* Get temperature forecast of 3 days in 3 hour interval from now of any major city in the world with graph visualization

To run weather_module.py, run the following command in the terminal
```python weather_module.py```.
After you have ran aforementioned command, you will be asked to enter the name of city of which you want to know the weather about. Similarly you have to enter its country code too. Then you will be prompted to a menu with three options:
1. To get current general weather information of input city
2. To get 3 days temperature forecast(average, minimum and maximum) of input city also you get a graph visualization of all the temperature in 3 hour interval from current time
3. Exit the program

Also this script score 8.76 out of 10 in pylint test.

## test_weather_app.py
This script is a unit test script which tests whether the value of longitude and latitude returned by `get_coordinate_info()` function is float or not. To run the unit test script, type the following command in the terminal
```python test_weather_app.py```. Keep in mind that both the scripts should be in same repository for this test to run.

## OpenWeatherMap API
The api used is the basic and free verison2.5 which lets about 60calls/minute and 1000calls/day. With this api we can get current weather info and 3-hour forecast of 3days of any major city. There is an api key in the file api_key.txt which is used by the weather_module.py to get weather information from openweathermap. Keep in mind that this text file should be in same directory as both scripts. 



