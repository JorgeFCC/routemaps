# Route map 
Using webview to get map from [project osrm](https://project-osrm.org/)
## Class   
The class person.dart is the one that defines the amount of information that is obtained, the registry of this must come accompanied of longitude and latitude  
## URL Generator
Used to obtain to construct the url that is going to be sent to map to construct the route, the route this defined by the order of the people that are shown in the right screen so that the collector knows to whom to ask for in each direction.
## Google Maps
At the end of the list of people to visit there is a button enabled to open the same points in google maps, the route can vary by the different algorithms used by each map to predict the shortest route. 
The code has two options to open it in the browser the option used and open it in the app (coded option but not used) at the moment in tests on Android devices by clicking on a map link automatically opens the Maps app.
