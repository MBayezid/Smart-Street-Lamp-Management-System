# Smart Street Lamp Management System

An IoT project designed to reduce energy consumption and maintenance costs, making existing street lamps smarter through the utilization of the NodeMCU-ESP8266 microcontroller and Firebase Realtime Database for data storage and remote control.

**Technologies Used:**

* **Microcontroller:** NodeMCU ESP8266
* **Programming Languages:** C++ (for ESP8266 - Arduino IDE), Java (for Android Application)
* **Cloud Platform:** Firebase Realtime Database
* **Android Development:** Android Studio

**Key Features:**

* **Remote On/Off Control:** Easily switch street lamps on or off remotely via the Android application.
* **Potential for Smart Scheduling:** (This could be expanded upon if implemented) Laying the groundwork for automated scheduling based on time or environmental conditions.
* **Real-time Status Monitoring:** The Android application displays the current on/off status of the street lamps based on data from Firebase.
* **Cost Reduction Focus:** Aims to minimize energy usage and lower maintenance needs through intelligent control.

**Setup Instructions:**

STEP 1:
Make sure you are using the latest version of Android Studio. Clone this project in Android Studio by following this tutorial: [https://www.geeksforgeeks.org/how-to-clone-android-project-from-github-in-android-studio/](https://www.geeksforgeeks.org/how-to-clone-android-project-from-github-in-android-studio/)
Use the following HTTP Link to Clone: `https://github.com/MBayezid/IoT_Android_Fireabase_NodeMcu-esp8266.git`

STEP 2:
Integrate Firebase into your Android project by following this tutorial: [https://www.geeksforgeeks.org/adding-firebase-to-android-app/](https://www.geeksforgeeks.org/adding-firebase-to-android-app/)
Ensure your Android Studio project is connected to a Firebase project.

STEP 3:
Add the Firebase Realtime Database service to your Firebase project. Configure the Realtime Database "Rules" for testing or according to the following structure:

**Create a Node (Object) named `Room1` and add child key-value pairs (the value must be a boolean type).**

![Screenshot of Firebase Rules Configuration](https://user-images.githubusercontent.com/42944621/213867374-6d71b6f3-c691-4f4e-8843-ce4bbf4f1ec7.png)

![Screenshot of Firebase Realtime Database Structure](https://user-images.githubusercontent.com/42944621/213867420-924e6dda-900d-4a1f-b254-24f9631f3c4e.png)

STEP 4:
Import the Android project into Android Studio's version control system using this link: `https://github.com/MBayezid/IoT_Android_Fireabase_NodeMcu-esp8266.git`

That's all! Once you add key-value pairs to the `Room1` node in your Firebase Realtime Database, the keys will appear on the home view of your Android application, reflecting the status of your virtual street lamps.
