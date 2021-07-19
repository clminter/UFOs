# UFOs

### Overview
Develop a URL capable of accepting user input to organize and display UFO data for various countries in the year 2010.  The data will be stored in a JavaScript array and will be dynamically filtered through the use of JavaScript, Bootstrap, and HTML.

### Results
Using the data provided a filtered seach function was created to loop through several catagories:
- Date (for 2010 only)
- City
- State
- Country
- Shape of Object

![image](https://user-images.githubusercontent.com/81878169/126087462-f9499a0a-edd4-4ddf-92f3-1225e794f316.png)

The user inputs data into any or all of the filters to narrow down their search of interest.  In the following example, NM for New Mexico was entered into the state filter.

![image](https://user-images.githubusercontent.com/81878169/126087725-d4894c30-9a15-4ed0-9d27-94c926e8b427.png)

In the following example, 'Triangle' was entered for the shape and CA was entered for the state.

![image](https://user-images.githubusercontent.com/81878169/126087865-4e06abce-9d1b-45b0-a0fd-77b165620ec6.png)

The filters can be reset by refreshing the page.

### Summary

A significant drawback to the design of this page is due to the fact that the data set is very limited in scope and the filtering system is capable of handling a much larger data set.  For instance, there is only one year considered and there is not necessarily an event occuring on each day of the year.  This makes using the date filter a hit and miss operation.  The same can be said in varying degrees for the other catagories also.  In the example below a date of 5/12/2010 was input.  There is no event for this date.  The user would find this to be very frustrating.

![image](https://user-images.githubusercontent.com/81878169/126088313-54187006-b575-4a0e-8fb4-feeddbdc554f.png)

#### Recommendations
  1.  Since the dates that have events are limited, a suggestion might be to create a drop-down calender menu that highlights dates that have events. The following is a good example from the recreation.gov website:

![image](https://user-images.githubusercontent.com/81878169/126088561-6a520577-6c0a-4d1e-89ed-19d7ac5aae9a.png)



  2. All cities, states and countries are also not represented in the data set.  A solution to searching for locations can be greatly simplified by using an interactive map showing locations of each event.  The following is a good example, also from the recreation.gov website:

![image](https://user-images.githubusercontent.com/81878169/126088482-a8e05816-08a4-43d7-b43f-0b5d34fa584a.png)
