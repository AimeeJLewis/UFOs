# UFOs
## Overview
The purpose of this UFO assignment was to create a table to organize UFO data that is stored as a JavaScript array. By making the table fully dynamic, the user is able to filter the data on a HTML webpage for easy viewing.  
## Results
Below is what the landing page of the HTML looks like.  
![Image 6-1-22 at 10 18 AM](https://user-images.githubusercontent.com/101950175/171499623-683f491a-381c-4079-a948-8ef6898800a0.png)
If you scroll down farther, you will find the start of the table along with the 'Filter Search' on the left hand side. 
![Image 6-1-22 at 10 19 AM](https://user-images.githubusercontent.com/101950175/171499648-7cf009bb-a69f-418b-9c37-1896cd26a66d.png)
The table can be filtered by Date, City, State, Country and Shape.  Please note that in order to filter, the data that you are filtering must be case sensitive. An example of filtering by 'triangle' in the Shape Filter.
![Image 6-1-22 at 10 25 AM](https://user-images.githubusercontent.com/101950175/171499661-0e7e9f4c-ef30-4701-b615-a5e0ebd0d8d6.png)
## Summary
One drawback of this design is you have the case sensitive when you filter the data.  You can't type in 'US' in the country and filter, you have to type be specific and use 'us'.  If we were to further develop this table, I'd recommend creating additional code to take in different user inputs for the filters and not have them be case sensitive so someone could type in 'US', 'Us', 'U.S.', etc in the country filter and it would always pull all of the data for the United States.  I'd also suggest creating a scrolling table where you see maybe 3-5 of the rows on the table vs. showing all of the rows on the landing page.  It would add a cleaner look on the page.
