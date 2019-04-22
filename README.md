# Technical Test


## Setup

The code has been created in Java using Eclipse Version: Oxygen.3a Release (4.7.3a)
The .zip file contains the whole Eclipse project folder,subfolders and libraries necessary.

The code is made of 6 classes.
  1. Driver class containing all the information related to each taxi.
  2. Controller class will print the console instruction 
    2.1 Enter pickup(lat and Long) and dropoff (lat and long)
  3. HandlerApi class will deal with the http request and all methods needed to connect to the API provided
  4. ServerController class will create a server with jetty on port 8005
  5. ServletHome class will take care of displaying the results on a web front-end
  6. ServletApi class is meant to display the results in JSON format but not fully implemented yet.

## Part 1

### Console application
Run the Controller class and follow the instruction displayed on console:

Enter pickup latitude <br /> 
Enter pickup longitude <br /> 
Enter drop-off latitude and drop-off longitude<br />

The result will be printed after.

Due to the try-catch the console will print also if one of the API is timing out
however the results will still be displayed for the API running correctly


## Part 2

### REST API
Run the ServeController class <br />
Open the browser and enter localhost:8005/techtest <br />
The page will present a simple input area for pickup and dropoff <br />
Once the search is submitted the output will be displayed just below it 
