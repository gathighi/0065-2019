# 0065-2019

A Front-end web application that uses HTML and CSS for the design and JavaScript that will handle all the operations such as initializing the map
and setting the location and the radius we want to view mechanical stores in. 
The design will be a single web page. The first page the users will see on accessing the web application, the landing page, will have two buttons. 
This will prompt the user to decide whether they want to see mechanical stores in their location or whether they would like to enter a location of their choosing. 
If the users were to select to see markers in their location, they would be prompted to allow access to their location. This would give the geolocation API permission 
to see your current location and use it as the centre of the map. Once permission is granted, the background would be hidden and replaced by a map whose 
centre is now the location passed using JavaScript. The system will automatically filter the information on the map, displaying only mechanical stores and their markers.
It would further only display those markers within a ten-kilometre radius from the location passed. From every marker the system would add the names of each
mechanical store to a list that the user can view at the bottom of the page. The idea is to have each of these mechanical stores in a list of links that would 
allow you to access their profiles
