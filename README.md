# Integrate-Google-map-into-Android-Studio

This is a simple project to integrate Google map into Android Studio.
Here, I generate Maps SDK for Android and API key.
These are the steps which I follow
1. Create New Project.
2. Select Template (Google Maps Activity).
3. Open google_maps_api.xml
4. Welcome page of my google cloud console account (https://console.cloud.google.com)

![3](https://user-images.githubusercontent.com/90547356/222925628-6b109064-d336-4d74-a77e-721ad23b395c.JPG)

5. Create a new project and Click Create API Key button.
6. Generated API KEY (Maps SDK for Android) 

<img src="https://user-images.githubusercontent.com/90547356/222925704-880f1dd8-e9a7-45b6-8e0b-558559404473.JPG" width="400" />

7. Check whether API services are enabled or not.

![7](https://user-images.githubusercontent.com/90547356/222925723-b2c8605d-af66-4414-a56c-8b9ef370b692.JPG)

8. Copy the API KEY and paste it to the google_maps_api.xml file (Android Studio).
9. Select the MapsActivity.java file from the APP->Java directory.
10. Run the default code (application) and get the emulator/device output.

<img src="https://user-images.githubusercontent.com/90547356/222925742-13352e8e-f197-49d2-9af0-bdbaf2d89ecf.JPG" width="200"/>


Then, add  Longitude and Latitude for Google Maps on Android (hardcoded values).
After that,
1. Implement the code inside the onCreate method and get the Longitude and Latitude using the getFromLocation() method.
2. Add your hometown address (String values).
3. Implement getLongitude(), getLatitude(), getCountryName().
4. Run and get the above three values using the Logcat view.
<img src="https://user-images.githubusercontent.com/90547356/222925855-33461354-bee4-403a-984b-d5c736fcb8e6.JPG" width="200" />

Finally, show the current location
