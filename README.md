# Trip-Advisor-Background-Reports
Scrapes Trip Advisor to write background paragraphs on hotels

This script writes short background paragraphs on hotels using data from Trip Advisor and Smith Travel Research. The paragraph cover TA rating, location, number of rooms, and different amenities. Here are the steps to gather the data needed for the template:

1) Go to http://www.str.com/product/Trend/CustomTrend

2) Type in the subject location, and use the filter options to narrow down your list.

3) Copy and paste the list of hotels from the box into an Excel file. You'll need to drag all of the 

attributes up to their hotel names.

4) Change the format of "Open Date" to a date format (preferably mm/dd/yyyy).

5) You need to manually input all of the associated Trip Advisor URLs. Just make it the last column of 

the spreadsheeet.

6) Final template should look something like this: https://s1.postimg.org/3jeng76rr3/Capture.png

STR Code - Name  - Distance - Rooms - CHain Scale - Last Month - Open Date - Associated - URL

7) Run the Trip Advisor Scrape notebook.
