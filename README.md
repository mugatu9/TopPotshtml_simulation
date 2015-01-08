
# TopPotshtml_simulation
Simulates Top Pot's donut demand in Seattle locations on an html page


PURPOSE:

Allows TopPot store owners to provide basic inputs regarding store activity, and provides them with calculated values for the number of donuts they need to have every hour and day.


What the Program does:

- Prompts the user to enter their store, and a values for few pre-defined attributes of that store.
- Stores each of those inputs from the user into arrays (instances of the constructor object) all store branches, with parameters for all key user inputs (location, the range of hourly foot traffic, the % of people entering the store, and # of donuts sold per person)
- Within the provided range, calculate random hourly values of foot traffic per location.
- Multiply hourly foot traffic by the % entered and avg. # of donuts sold to generate # of total sales per hour, and store these values in an array.
- Output the results of each array into cells of an empty table in the browser. 

