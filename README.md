# Hackathon11
Read Me

The application that we aim to build is a safeguarding application to request a verified UCL guard or student at a given time.
The app will contain a request button which leads to a menu containing different options based on the purpose of the request since some requests are more urgent or in need of specialisms than others. 

The options are safeguarding, for when a person is walking to or from campus within a specific radius and is uncomfortable while alone and may need first aid. This can be useful for late classes to avoid any accidents that might occur during nighttime.

The second option is company, for example due to mental health reasons or feeling lonely. If a person simply wishes to have company, then a UCL wellbeing staff member or volunteer can be sent to them.

The way this app works is by getting geolocations from both the requesting person and the guard/volunteer.

The concept in itself is like UBER. Once you click request, your location is saved and the distance to the nearest guards is calculated. The nearest guard will receive the sender’s location on an interactive map with directions. A timer then appears on the receiver’s screen displaying the remaining time before a guard is predicted to arrive, a clear profile picture and the guard’s name. In case of safeguarding, an alarm button will also be displayed to produce a loud sound in case of danger.

If a single guard receives two requests at the same time, the priority is given to the higher emergency request. If both requests are equal emergency level, priority will be given to the nearest requestor.

The app is using a react geolocation API and the guards’ locations are saved on an Excel sheet in the locations.xls file.

The excel.py code adds elements to the list and reads elements from the list to connect the location code with the Excel sheet.

Unfortunately, with the given timeframe we were unable to make the app fully run or link the Excel code with the app code.

Ideally, in order to run the app, what would be required is:
•	developer must have expo (how to install it: https://docs.expo.dev/get-started/installation/)
•	developer must install react-native-maps, react-native-geolocation-service, react-native-vector-icons/Ionicons, react-native-sound. 

For npm, running the following commands would work:

•	npm install react-native-maps
•	npm install react-native-geolocation-service
•	npm install react-native-vector-icons/Ionicons
•	npm install react-native-sound

For yarn install, instead use:
•	yarn install react-native-maps
•	yarn install react-native-geolocation-service
•	yarn install react-native-vector-icons/Ionicons
•	yarn install react-native-sound
