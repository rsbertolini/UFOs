# UFOs


## Overview of Project
The purpose of this project was to create a web page using html that would accept 5 different field inputs from a user.  A JavaScript listener
would be monitoring for changes to those fields and send the new inputs to functions written in the JavaScript code that would update the table. 
As more filter inputs are received the table data is filtered to a greater degree.


## Results
The web page will present with placeholder data in the fields so the user knows the format of the text.  To perform a search, you can filter on 
as few or as many fields as you like.  Entering data in 1 field will immediately prompt the listenerto send the newly changed data to the updateFilter 
function and rebuild the table.  
![Filter1 image](/static/images/Filter1.PNG)

You can further refine your search by querying for more fields.  As you send more filter criteria, your data will become more refined.  Here we simply updated
the City filter and get all results for all dates for that 1 city.
![Filter2 image](/static/images/Filter2.PNG)

Here is an example of all 5 fields being filtered on.
![Filter3 image](/static/images/Filter3.PNG)

## Summary
  * One drawback is that the data looks for a strict comparison of the filter elements so we are relying on the user to input the fields in the correct format without
  typos.
  
  * Further development may include field masks and/or dynamic picklists to help the user know what data is available.  For example the date field could include a calendar
   option instead of requiring the user to enter the data in the proper date format.  Dynamic picklists could be used to aid the user towards rows that exist.  For instance,
   if a user entered a specific date, the next city field cold present a picklist of cities that have rows in the database with that date.
