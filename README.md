# seatgeek broadway API function
API Wrapper function to get Cheapest Broadway Ticket from SeatGeek

This is an assignment for Modern Data Structure class. In this assignment I used SeatGeek Events API. This API let me to obtain a directory of live events in the United States and Canada. I used this API to retrieve Broadway show information such as number of ticket available, average price, city, name of the theater, lowest price, and highest_price. At the end of the file, you can find a function to get n cheapest Broadway (or Off-Broadway) shows by range of date from SeatGeek website called `seatgeek_broadway_cheapest`

Parameters of the function are:
-------
- date_start : str
    Date start of the search in YYYY-MM-DD format.
- date_end : str
    Date end of the search in YYYY-MM-DD format.
- city : str
    Name of the city of broadway show you want to look at recommended to use 'New York'.
- n : int
    Number of cheapest shows you want to observe.
- type : str
    Method to find cheapest ticket by lowest ticket price in the show ('lowest') or average ticket price ('average').
      
Examples
--------
>>> seatgeek_broadway_cheapest(date_start = '2021-12-01',date_end = '2021-12-31',n = 3, type = 'average')
