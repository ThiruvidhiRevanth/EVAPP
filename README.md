# Family Safety and Vehicle Management App

This mobile application is designed to enhance **family safety** and **vehicle management**. It is developed using **FlutterFlow** and **Firebase** to provide a no-code solution for tracking family members' locations, managing vehicles, and receiving critical alerts. The app integrates **Firebase** for authentication, real-time database management, and push notifications, and uses **Google Maps API** for location tracking.

## Features

### 1. **Family Safety Monitoring**
   - **Location Sharing**: Track the real-time locations of family members.
   - **Emergency Alerts**: Instantly send alerts to designated family members in case of an emergency.
   - **Safety Zones**: Create geofenced areas (e.g., home, school) and receive notifications when a family member enters or exits a zone.
   
### 2. **Vehicle Management**
   - **Vehicle Tracking**: Monitor the real-time location of vehicles using GPS.
   - **Maintenance Reminders**: Get reminders for vehicle maintenance tasks such as oil changes, tire rotations, etc.
   - **Fuel Tracking**: Track fuel consumption and set reminders for refueling.
   
### 3. **User Profiles**
   - Create and manage profiles for family members and vehicles for quick access to relevant data.

### 4. **Notifications**
   - Receive critical notifications for events such as emergency alerts, low fuel levels, or missed maintenance tasks.

### 5. **Privacy and Security**
   - All user data is securely stored using **Firebase**, and users have control over what information is shared.

---

## App Structure

The app is structured around two main domains:
1. **Family Safety**: Location tracking for family members and emergency alerts.
2. **Vehicle Management**: Vehicle tracking, maintenance reminders, and fuel tracking.

---

## Getting Started

### Prerequisites
Before setting up the project, ensure you have the following:
- A **FlutterFlow** account (free or paid).
- A **Firebase** account for authentication, real-time database, and push notifications.
- **Google Maps API** key for location tracking.

### Setting Up the Project
1. **Create a FlutterFlow Project**:
   - Log in to your FlutterFlow account and create a new project.
   - You can either start from scratch or use a template for location tracking and Firebase integration.

2. **Firebase Setup**:
   - Create a new Firebase project in the [Firebase Console](https://console.firebase.google.com/).
   - Enable Firebase Authentication (email, Google login, or other methods).
   - Set up **Firebase Firestore** or **Firebase Realtime Database** to store user and vehicle data.
   - Enable **Firebase Cloud Messaging (FCM)** for push notifications.

3. **Integrate Firebase with FlutterFlow**:
   - In FlutterFlow, go to **Settings** > **Firebase** and link your Firebase project.
   - Set up Firebase Authentication using the methods you've enabled (email/password or Google).
   - Set up Firestore or Realtime Database to manage the data for family members, vehicles, and notifications.
   - Add Firebase Cloud Messaging for handling push notifications when important events occur (e.g., emergency alerts, vehicle maintenance reminders).

4. **Set Up Google Maps API**:
   - Go to the [Google Cloud Console](https://console.cloud.google.com/), create a new project, and enable the **Google Maps API**.
   - Obtain your **Google Maps API Key** and configure it in your FlutterFlow project under **Settings** > **Google Maps**.

5. **Deploying the App**:
   - After configuring Firebase and Google Maps API, test the app on your emulator or real device using FlutterFlow's built-in test features.
   - Once everything is set up, you can deploy the app to the App Store or Google Play.

---

## How to Use the App

1. **Sign Up / Login**:
   - Users can create an account or log in using Firebase Authentication (email, password, or Google).

2. **Add Family Members**:
   - Add family members to the app by entering their names and linking their devices for location tracking.

3. **Add Vehicles**:
   - Enter vehicle details such as make, model, and license plate.
   - Enable vehicle GPS tracking to monitor real-time locations.

4. **Set Safety Zones**:
   - Create geofenced zones (e.g., "Home", "School") to receive notifications when family members enter or leave these zones.

5. **Receive Notifications**:
   - Enable push notifications for critical events such as:
     - Emergency alerts from family members.
     - Low fuel levels in vehicles.
     - Upcoming maintenance reminders.

---

## Technologies Used

- **FlutterFlow**: A no-code platform used to design and build the app's user interface and functionality.
- **Firebase**: Provides authentication, real-time database management, and push notifications.
  - Firebase Authentication for user login and registration.
  - Firebase Firestore or Realtime Database for storing data.
  - Firebase Cloud Messaging (FCM) for push notifications.
- **Google Maps API**: Used for tracking real-time locations of family members and vehicles.
- **Flutter**: The mobile app framework generated by FlutterFlow for building and deploying the app.

---

## Contributing

Contributions to the app are welcome! If you'd like to contribute, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Write tests for any new features.
4. Submit a pull request with a description of the changes.

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

## Troubleshooting

- **Location Tracking Not Working**: Ensure the app has the necessary permissions to access the device's location, and that Google Maps API is correctly set up.
- **Push Notifications Not Received**: Verify that Firebase Cloud Messaging is correctly configured and that the device allows push notifications.
- **Vehicle Data Not Syncing**: Ensure Firebase Firestore or Realtime Database is configured properly and that the device has an active internet connection.

---

## Contact

If you have any questions, suggestions, or issues, feel free to contact us:

- **Email**: thiruvidhirevanth@gmail.com
- **Website**: [www.example.com](http://www.example.com)
