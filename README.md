### Analysis and prediction of fares of flights in India.
#### Description 
- Data set of airline fares in India from March to June 2019.
- The dataset contains a total of 10683 rows and 11 variables: 
    - Airline: Name of the airline.
    - Source: The starting point of the flight.
    - Destination: The destination of the flight.
    - Route: The route of the flight.
    - Total_Stops: The total number of stops between the start and end points.
    - Additional_Info: Additional flight information.
    - Price: The price of the flight ticket.
    - Date_of_Journey: The date of the flight.
    - Dept_Time: The time at which the flight begins.
    - Arrival_Time: Flight arrival time.
    - Duration: Total flight time.
- Input: Airline, Source, Destination, Route, Total_Stops, Additional_Info, Duration, Date_of_Journey,Dep_Time, Arrival_Time.
- Ouput: Price.
- Measure: $R^2$.
#### Install libraries
- pip install pyspark
- pip install pyspellchecker
- pip install numpy
- pip install pandas
- pip install matplotlib

#### Using regression algorithms
- Linear Regression
- Decision Tree
- Random Forest
- Gradient Boosted Tree