# CHARTERMATCH ~ Flight Information Display
## Rules
The test application should be written predominantly using Java. Using HTML, CSS & Javascript for the display of data
will be looked at favourably, as this will help show your front-end abilities.
We don't spend too much time on it. We estimate that this task should take 1 ~ 3 hours, give or take ...

## What it should do
The application should consume the [flight data](flights.csv) file and display all flights for the current day and time,
in chronological order. Flights that are in the past should be displayed as "Departed"  -- 
similar to a Flight Information Display that you might find in an airport.

In addition you should adhere to the following conditions:

1) Spring Boot should be used as the basis of the project. 
1) It must use Gradle as the build mechanism. 
1) All dependent libraries must be publicly available. 
1) Clear and concise instructions for how to build and run the application should be included within the code, e.g. `README.md`
1) The code must be your own work. If you have a strong case to use a small code snippet of someone else's e.g. a
boilerplate function, it must be clearly commented and attributed to the original author.
1) The flight data cannot be changed, and must be loaded from the CSV file, so it can easily be replaced with another file.

**_You should choose an approach that you feel demonstrates your expertise and suitability for the position._**

## Supporting Data
The [flight data](flights.csv) is a simple comma-separated file containing the following:

| Departure Time | Destination | Destination Airport IATA | Flight No | Sunday | Monday | Tuesday | Wednesday | Thursday | Friday | Saturday | 
|----------------|-------------|--------------------------|-----------|--------|--------|---------|-----------|----------|--------|----------| 
| 09:00          | Nice        | NCE                      | CM033     |        |        | x       |           |          |        |          | 
| 10:00          | Nice        | NCE                      | CM033     |        |        |         |           | x        |        | x        | 
| 11:05          | Amsterdam   | AMS                      | CM029     | x      | x      | x       | x         | x        | x      | x        | 
| 12:20          | Prague      | PRG                      | CM093     |        |        | x       |           |          |        |          | 
| 09:00          | Rome        | FCO                      | CM089     |        | x      |         |           |          |        |          | 
| 10:10          | Rome        | FCO                      | CM089     |        |        |         |           |          | x      |          | 
| 10:15          | Málaga      | AGP                      | CM063     |        |        | x       |           |          |        |          | 
| 10:15          | Málaga      | AGP                      | CM063     |        | x      |         |           | x        |        |          | 
| 10:15          | Berlin      | TXL                      | CM043     | x      |        |         |           |          | x      | x        | 
| 10:25          | Berlin      | TXL                      | CM043     |        |        |         |           | x        |        |          | 
| 10:35          | Berlin      | TXL                      | CM043     |        | x      | x       | x         |          |        |          | 
| 15:35          | Berlin      | TXL                      | CM044     | x      | x      | x       | x         | x        | x      | x        | 
| 12:25          | Minsk       | MSQ                      | CM065     |        |        |         | x         |          |        |          | 
| 12:40          | Minsk       | MSQ                      | CM065     | x      |        |         |           |          |        |          | 
| 10:10          | London      | LGW                      | CM049     | x      |        |         |           |          |        |          | 
| 10:15          | London      | LGW                      | CM027     |        |        |         | x         |          |        |          | 
| 11:00          | London      | LGW                      | CM027     |        | x      |         |           |          |        |          | 
| 11:10          | London      | LGW                      | CM049     |        | x      |         |           |          |        |          | 
| 11:20          | London      | LGW                      | CM027     |        |        |         |           |          | x      | x        | 
| 11:35          | London      | LGW                      | CM027     |        |        |         |           | x        |        |          | 
| 11:45          | London      | LGW                      | CM027     | x      |        | x       |           |          |        |          | 
| 11:45          | London      | LGW                      | CM049     |        |        |         | x         |          |        |          | 
| 13:00          | London      | LGW                      | CM015     | x      | x      | x       | x         | x        | x      | x        | 
| 09:00          | Lviv        | LWO                      | CM089     |        | x      |         |           |          |        |          | 
| 09:00          | Lviv        | LWO                      | CM097     | x      |        |         |           |          |        |          | 
| 10:10          | Lviv        | LWO                      | CM089     |        |        |         |           |          | x      |          | 
| 09:00          | Geneva      | GVA                      | CM097     | x      |        |         |           |          |        |          | 


The ``x`` denotes days that the flight operates. 

## How to submit your test
**PLEASE DO NOT TRY AND PUSH YOUR CODE INTO THIS REPOSITORY.** This project is merely a location to hold the test data 
and description of the test.

Preferably you will submit your code via a public repository you own e.g. yor own Github or Bitbucket account. However,
you may also submit your code via email or file sharing mechanism - e.g. Dropbox - using an archive, such as zip file or 
tarball (please consider the size of the file before emailing). 