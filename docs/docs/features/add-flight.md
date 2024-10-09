---
sidebar_position: 1
---

# Add Flight

The main purpose of this application is to log flights.
To add one, click on the first button in the bottom navigation bar.

<img src={require('./img/add-flight.png').default} width="100%" alt="Add flight" />

## Date and Time

:::tip Timezones
Times are represented in the local timezone of the airport.
So if you are flying from New York to London, the departure time should be entered in Eastern Time and the arrival time
in Greenwich Mean Time.
:::

The departure date is required, the rest are optional.
If a arrival time is entered without an arrival date, the date will be assumed to be the same as the departure date.


## Origin and Destination

These fields are required.
Start typing the name of the airport and select the correct one from the list.
For the most consistent results, search using the ICAO or IATA code. 

## From flight number

If you have a flight number, you can enter it at the top.
Clicking "Search" will try to fill in the origin, destination, and airline fields for you.