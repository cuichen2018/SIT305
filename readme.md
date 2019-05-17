#SIT305 Android Project (Parking APP)

CHENMING CUI & WENYI LIANG

The app provide the parking lot searching and navigating functions. Allow users to see a parking lot list and details of diferent parkings.

The pariking list provide sorting by distance and price. The details includes the map overview, remaining areas and price list. 

The details of parkings page provide a button for navigation to the particular parking lot. The Baidu map will provide a best route for driving.  

The login page provide register and notification for duplicate username. The register page needs users to input password twice to confirm the password 

Users can login after registration. The client will keep the user logged in unless the user press logout to exit the current account. 

The about page includes the information of the Developers and a Link to Github repository. 



The navigation of the this app is based on the baidu map. The baidu map will get the current location from the device and return the navigation as well as the current weather information. After getting the longitude and lagitude information of the Parking lot. The navigation page will call the Baidu API to implement navigation.  

The registration information of users will be stored into the sharedpreference. The username and password are stored as a key-value pair. Different account are separated using ";". No encryption is provided currently which can be implemented in the future. 

The parking list is using the recycleview and reuse the item which will save more ram. And the item is using the cardview in support v7 which will provide a more conspicuous 3D effect. 

The sliding menu has a dynamic effect which will provide a more user-friendly and beautiful interface.
