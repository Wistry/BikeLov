# BikeLov <img src="./assets/logo.png" alt="Logo" width="110" align="right">
<p align="right">
 |  <a href="./README.md">ES</a> | 
</p>

Mobile app for cyclists, focused on promoting **group rides** and user interaction.

---

## Index

- [Summary](#summary)
- [Features](#features)
- [Technical Details](#technical-details)
- [Compatibility](#compatibility)
- [Demo](#demo)

---

## Summary

BikeLov combines the **sport** world with a strong **social** focus. Specifically designed for **group cycling rides**, it allows users to **see in real time** the **position** and **heart rate** of their companions on the map, helping optimize group performance.

The app is mainly divided into two parts:

• **Sport:** Provides everything needed for cycling routes, from route creation via maps, sensor tracking and key parameter monitoring, to detailed analysis after completing the ride.

• **Social:** Integrates features similar to modern social networks. Share routes, follow other users, create cycling groups, and maintain private chats.

---

## Features

1. **Create and share routes:** Map interface to trace custom routes and share them with others.

2. **Real-time tracking:**  Live visualization of your route and your companions'.

3. **Cycling group management:**  Create, join, and manage user groups.

4. **User following and private messaging:**  Add users and communicate directly.

5. **Social feed:**  Posts visible to the users you follow.

6. **Route analysis:**  Stats and summaries for each ride.

---

## Technical Details

BikeLov has been developed using an **MVVM** architecture to improve code organization and ease maintenance.

**Technologies used:**

- **Frontend:** Android Studio, Java, Android Jetpack  
- **Backend:** Google Cloud, Firebase, and Cloudinary  
- **Database:** Firebase Realtime Database (NoSQL), optimized for real-time data  
- **Additional services:** Firebase Authentication, Google Maps SDK, Sensor API (heart rate)

---

## Compatibility

BikeLov is designed for devices with **Android 8.0 (API 26)** or higher.

**Sensors:** Compatible only with heart rate sensors from the **Polar** brand, thanks to its proprietary API and wide Android support. Sensors from other brands are not integrated due to API limitations and stability issues.

**Dependencies:** The app requires location permissions and Bluetooth sensor access for full functionality.

---

## Demo

[![Demo](./assets/demo.png)](https://youtu.be/EHBOCG4SexE)

---
