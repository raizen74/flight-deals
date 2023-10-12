# Flight deals search engine
The goal of the project is to email me if some flight bargain is found, the program does this steps:
- Read flight prices to several destinations from a Google sheet file using the **Sheety API**.
- Use the **Tequila API** to fetch flight data, searching for flights from tomorrow until six months from now, I set the trip duration in the range of 7-28 days and a max stopovers = 1.
- If there are cheaper flights than the ones in the Google sheet, email me with the flight data. 
