# Applied-Data-Science-Capstone-Project-

2.  Describe the data that you will be using to solve the problem or execute your idea. Remember that you will need to use 
the Foursquare location data to solve the problem or execute your idea. You can absolutely use other datasets in combination 
with the Foursquare location data. So make sure that you provide adequate explanation and discussion, with examples, 
of the data that you will be using, even if it is only Foursquare location data.

I will take the postal codes from all boroughs and neighborhoods in Mexico City from https://micodigopostal.org/. 
For example, here there are some of the postal codes from neighborhoods from the borough “Cuauhtémoc” in Mexico City: https://micodigopostal.org/ciudad-de-mexico/cuauhtemoc/
Then, from the postal codes of this type of tables I will use pgeocode, a python library that finds the GPS coordinates, region name, and municipality names from postal codes. 
After, I will input this information in Foursquare, to search for different types of Restaurants in the streets of Mexico-City neighborhoods.  
Here is an example of a vegan/vegetarian restaurant in Mexico City:
https://foursquare.com/explore?mode=url&near=Mexico%20City%2C%20DF%2C%20Mexico&nearGeoId=72057594041458533&q=Radha%20Krishna 
Finally, I will use the statistics of restaurants in Mexico City to give tourists suggestions of where to find the right restaurant for them. 
