# Real-Estate

---
a comprehensive real estate application designed to simplify property management and transactions for buyers, sellers, and agents.

---
## Table of Contents
- [Features](#✨-features)  
- [Installation](#🚀-installation)  
- [Technology Stack](#💻-technology-stack)
- [Screenshots](#📸-screenshots)
- [License](#📝-license)  

---

# ✨ **Features**

## **Admin Features**
- **Dashboard**
  - Get real-time **analytics** and an overview of all key metrics, including revenue, user roles, property types, and valuations.
    
- **User Management**
  - View and manage users categorized by role (e.g., **agents** and **users**).
  - Track the **total number of agents** and **users**.

---

## **Agent Features**
- **Property Management**
  - View and categorize properties by type (e.g., **Land**, **Rental**, **House**).
  - Track the **count** of each property type.
  - Perform **CRUD operations**: Create, Read, Update, and Delete property listings.

- **Valuation Management**
  - View and monitor the **status of property valuations** (e.g., **completed** vs **pending**).
  - **Update valuation status**: Mark valuations as completed when the property valuation process is finalized.

- **Chat Feature**
  - Respond to user inquiries regarding properties.
  - Communicate with users when they request a property valuation.

---

## **User Features**
- **Profile Management**
  - Create, update, and manage your user profile securely using **Firebase Authentication**.

- **Purchases**
  - Make **property purchases** and view your **purchase history**.
  - Access detailed **purchase data**, such as amount spent and purchase date.

- **Property View**
  - Browse and view **property listings** categorized by type (e.g., **Land**, **Rental**, **House**).

- **Valuation Requests**
  - Request a valuation for a property.
  - Track the status of valuations (**completed** or **pending**).

- **Chat Feature**
  - Initiate a chat with an agent for property inquiries or valuation requests.

- **Transactions**
  - Complete transactions to **purchase properties**.

- **Bookmarking**
  - Bookmark properties for easy access and review later.

---
## 🚀 **Installation**

Follow these steps to set up and run the Kotlin app on your local machine:

### Prerequisites

1. **Android Studio**
   - Download and install the latest version of [Android Studio](https://developer.android.com/studio).
   - Ensure the following tools and plugins are installed:
     - Kotlin plugin
     - Android SDK (version required by the app)
     - Gradle build system

2. **Java Development Kit (JDK)**
   - Install JDK 11 or later. You can download it from [Oracle](https://www.oracle.com/java/technologies/javase-downloads.html) or [AdoptOpenJDK](https://adoptopenjdk.net/).

3. **Firebase Tools (if applicable)**
   - If the app uses Firebase, create a Firebase project and download the `google-services.json` file.
   - Place the `google-services.json` file in the `app/` directory of the project.

---

### Installation Steps

1. **Clone the Repository**
   Clone this repository to your local machine using Git:
   ```bash
   git clone https://github.com/Sblasta7/PennyWise.git
   cd PennyWise
   ```

2. **Open the Project in Android Studio**
   - Launch Android Studio.
   - Open the cloned project folder (`File > Open`).
   - Wait for Gradle to sync. If prompted, update any outdated dependencies.

3. **Sync Gradle**
   - Ensure all dependencies are downloaded and configured by syncing the Gradle files:
     - In Android Studio, navigate to `File > Sync Project with Gradle Files`.
   - Resolve any errors or missing dependencies that may appear.

4. **Connect a Device or Emulator**
   - Use a physical Android device:
     - Enable "Developer Mode" and "USB Debugging" on your device.
     - Connect the device via USB and ensure it appears in Android Studio under "Device Manager."
   - Or set up an Android Emulator:
     - In Android Studio, navigate to `Tools > Device Manager` and create a new virtual device.

5. **Run the App**
   - In Android Studio, select the device or emulator where you want to run the app.
   - Click the "Run" button (green triangle) or press **Shift + F10** to build and deploy the app.

---

### Troubleshooting

- **Gradle Sync Issues**  
  If Gradle fails to sync, ensure that:
  - You have a stable internet connection.
  - You’ve updated Android Studio and all SDK tools to their latest versions.

- **Firebase Errors**  
  If the app uses Firebase and you encounter errors:
  - Confirm that the `google-services.json` file is correctly placed in the `app/` directory.
  - Verify that your Firebase project settings match the app package name.

- **Device Not Recognized**  
  If your physical device is not detected:
  - Ensure the USB drivers for your device are installed.
  - Check that "USB Debugging" is enabled.

For further assistance, feel free to open an issue in the repository.

---

You’re all set! 🎉 If you encounter any additional issues, don’t hesitate to reach out.

---

## 💻 **Technology Stack**  

[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/en)  
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white)](https://firebase.google.com/)
[![Firestore](https://img.shields.io/badge/Firestore-FFBB33?style=for-the-badge&logo=firebase&logoColor=white)](https://firebase.google.com/docs/firestore)
[![Firebase Authentication](https://img.shields.io/badge/Firebase_Authentication-FFCA28?style=for-the-badge&logo=firebase&logoColor=white)](https://firebase.google.com/docs/auth)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](https://github.com/features/actions)


---
## 📸 **Screenshots**

### User

| Feature           | Screenshot                                                                                     |
|-------------------|------------------------------------------------------------------------------------------------|
| Home Page         | <img src="https://github.com/user-attachments/assets/8d930aee-b67b-46b6-978f-b380b75a1f17" width="200" height="403"/> |
| Property details Page | <img src="https://github.com/user-attachments/assets/8450384b-c26b-4e21-817d-ea0f38507e22" width="200" height="403"/> |
| Contact Agent     | <img src="https://github.com/user-attachments/assets/58f86570-66cb-459b-9753-9474f4e24f56" width="200" height="403"/> |
| Chat Page         | <img src="https://github.com/user-attachments/assets/f9f530f9-4e4c-4096-a020-8e451ff624d6" width="200" height="403"/> |
| Valuations Page   | <img src="https://github.com/user-attachments/assets/f5f45ca8-19f4-4eb0-8333-d3db79ad3706" width="200" height="403"/> |
| Free valuation Page | <img src="https://github.com/user-attachments/assets/1bdaab0b-f481-4220-a4bb-e4a9a1b93eb2" width="200" height="403"/> |
| Bookmarks Page    | <img src="https://github.com/user-attachments/assets/4c9d513c-4252-488b-9cba-d8969c99ace8" width="200" height="403"/> |
| Settings Page     | <img src="https://github.com/user-attachments/assets/d09a57b7-0b2a-4ffe-b65f-346c4d1f95b8" width="200" height="403"/> |


### Agent

| Feature           | Screenshot                                                                                     |
|-------------------|------------------------------------------------------------------------------------------------|
| Home Page         | <img src="https://github.com/user-attachments/assets/8d930aee-b67b-46b6-978f-b380b75a1f17" width="200" height="403"/> |
| Property details Page | <img src="https://github.com/user-attachments/assets/8450384b-c26b-4e21-817d-ea0f38507e22" width="200" height="403"/> |
| Valuations Page   | <img src="https://github.com/user-attachments/assets/edd523ce-aa61-4f72-9b8f-de9cd371ecb0" width="200" height="403"/> <img src="https://github.com/user-attachments/assets/60f9a304-47ea-4cf1-a7b8-f71d3df18e62" width="200" height="403"/>|
| Create Property Page | <img src="https://github.com/user-attachments/assets/8808ac65-49d5-49ac-b334-fd9c06e8bfe9" width="200" height="403"/> |
| Select Images Page   | <img src="https://github.com/user-attachments/assets/b4d224dd-e406-408c-868a-52838ec61fdd" width="200" height="403"/> <img src="https://github.com/user-attachments/assets/ec5d8bc7-d0c8-4f79-9f3a-0b7c496bbc88" width="200" height="403"/> |
| Select Location Page | <img src="https://github.com/user-attachments/assets/35af9ce1-9240-4663-81cc-3a2616c9c1e1" width="200" height="403"/> |
| Select Owner Page    | <img src="https://github.com/user-attachments/assets/fc92d794-ac0a-4e07-acd0-dc86c83794e4" width="200" height="403"/> |



### Admin

| Feature           | Screenshot                                                                                     |
|-------------------|------------------------------------------------------------------------------------------------|
| Analytics Page        | <img src="https://github.com/user-attachments/assets/d47b9dec-8fbc-4943-a469-b6000a3729a9" width="200" height="403"/> |
| Property details Page | <img src="https://github.com/user-attachments/assets/7480d4a0-9cc0-44c2-9754-a6fb4072607d" width="200" height="403"/> |


---
## 📝 **License**

This project is licensed under the [MIT License](LICENSE).  
Feel free to use, modify, and distribute it as per the license terms.



