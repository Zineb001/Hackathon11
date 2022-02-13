# Hackathon11
Read Me

The application that we aim to build is a safeguarding application to request a UCL staff company at a given time.
The app will contain a request button which leads to a menu containing different options based on the purpose of the request since some are more urgent than others. 
The options are safeguarding, for when a person is walking to or from campus within a specific radius and is uncomfortable while alone. This can be useful for late classes to avoid any accidents that might occur during nighttime.
The second option is company, for example due to mental health reasons. If a person simply wishes to have company, then a UCL wellbeing staff member can be sent to them.
The way this app works is by getting geolocations from both the requesting person and the guard.
The concept in itself is like UBER, once you click request, your location is saved and the distance to the nearest guards is calculated. The guards will receive the sender’s location on an interactive map with directions. And a timer appears on the receiver’s screen displaying the remaining time before a guard arrives, a clear profile picture and the guard’s details. In case of safeguarding, an alarm button will also be displayed to produce a loud sound in case of danger.
If a single guard receives two requests at the same time, the priority is given to the emergency request.
The app is using a react geolocation API and the guards’ locations are saved on an excel sheet in the locations.xls file.
The excel.py code adds elements to the list and reads elements from the list to connect the location code with the excel sheet.
Unfortunately, with the given timeframe we were unable to make the app fully run or link the excel code with the app code.
Ideally, in order to run the app, what would be required is:
•	developer must have expo (how to install it: https://docs.expo.dev/get-started/installation/)
•	developer must install react-native-maps, react-native-geolocation-service, react-native-vector-icons/Ionicons, react-native-sound. For npm, running the following commands would work:
•	
•	npm install react-native-maps
•	npm install react-native-geolocation-service
•	npm install react-native-vector-icons/Ionicons
•	npm install react-native-sound
•	
•	For yarn install, instead use:
•	yarn install react-native-maps
•	yarn install react-native-geolocation-service
•	yarn install react-native-vector-icons/Ionicons
•	yarn install react-native-sound
