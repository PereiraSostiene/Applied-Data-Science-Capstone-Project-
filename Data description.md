# Applied-Data-Science-Capstone-Project-

I will take the postal codes from all boroughs and neighborhoods in Mexico City from https://micodigopostal.org/. 
For example, here there are some of the postal codes from neighborhoods from the borough “Cuauhtémoc” in Mexico City:
![image](https://user-images.githubusercontent.com/40398251/126818328-bea08683-5384-4436-bd13-446ad55ad8e4.png)

Then, from the postal codes of this type of tables I will use pgeocode, a python library that finds the GPS coordinates, 
region name, and municipality names from postal codes. After, I will input this information in Foursquare, 
to search for different types of Restaurants in the streets of Mexico-City neighborhoods.  

Here is an example of a vegan/vegetarian restaurant in Mexico City:
https://foursquare.com/explore?mode=url&near=Mexico%20City%2C%20DF%2C%20Mexico&nearGeoId=72057594041458533&q=Radha%20Krishna 
![image](https://user-images.githubusercontent.com/40398251/126818440-2473bf2c-5752-46bd-9d5a-5075dae89c44.png)

Finally, I will use the statistics of restaurant in Mexico City to give tourists suggestions of where to find the right restaurant for them. 
