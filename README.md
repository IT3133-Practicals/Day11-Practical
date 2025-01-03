# Day 11 Practical - React Native Navigation 🧭📱

Welcome to the **Day 11 Practical** for React Native Navigation! This project demonstrates how to implement navigation between different screens using **React Navigation** in a React Native app. It includes basic navigation setup with **Stack Navigation**, where users can navigate between three screens: **Home**, **Contact Us**, and **About Us**.

## Table of Contents 📑
- [Features](#features)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
- [Prerequisites 🛠️](#prerequisites)
- [Installation 💾](#installation)
- [Running the App 🎮](#running-the-app)
- [Key Files 📂](#key-files)
- [Contributing 🤝](#contributing)
- [Outputs 📸](#outputs)
- [License 📄](#license)

## Features 🚀
- **Home Screen**: A simple screen with some introductory text and buttons to navigate to other screens.
- **Contact Us Screen**: A form where users can input their name, email, phone number, and a message. A button to navigate to the "About Us" screen.
- **About Us Screen**: Provides information about the app and company.
- **Stack Navigation**: Implemented using React Navigation's **createNativeStackNavigator**.
- **Responsive Layout**: Designed to be mobile-friendly with **react-native-paper** components.

## Technologies ⚙️
This project uses the following technologies:
- **React Native 🟢**: A JavaScript framework for building native mobile applications.
- **React Navigation 🧭**: A navigation library for React Native that enables easy screen transitions.
- **React Native Paper 🎨**: A UI library that provides pre-built components such as buttons, text inputs, and more.
- **JavaScript (ES6+) 📜**: Modern JavaScript for clean, efficient code.
- **VS Code 💻**: The code editor used for development.

## Getting Started 🏁

Follow these steps to get this project running on your local machine:

### Prerequisites 🛠️
Make sure you have the following installed:
- **Node.js**: Install from [Node.js Official Website](https://nodejs.org/).
- **React Native CLI**: Install globally by running:
  ```bash
  npm install -g react-native-cli
  ```

### Installation 💾
Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/react-native-navigation-app.git
cd react-native-navigation-app
```

Install the required dependencies:

```bash
npm install
```

### Running the App 🎮

After the installation is complete, you can start the app on an Android or iOS device/emulator.

#### For Android:
```bash
npx react-native run-android
```

#### For iOS:
```bash
npx react-native run-ios
```

The app should now be running on your device or emulator.

```

## Key Files 📂
- **App.js**: The main app component that configures the **Stack Navigator** and sets up the screens.
- **components/Home.js**: The Home screen with introductory text and buttons to navigate to other screens.
- **components/ContactUs.js**: The Contact Us screen where users can fill out a form.
- **components/AboutUs.js**: The About Us screen with details about the app.
- **src/styles/**: Folder for styling files used in different screens.

## Contributing 🤝
We welcome contributions to improve this project! If you'd like to contribute, please follow these steps:

1. **Fork the repository**.
2. **Create a new branch**:
   ```bash
   git checkout -b feature-name
   ```
3. **Make your changes**.
4. **Commit your changes**:
   ```bash
   git commit -am 'Add feature'
   ```
5. **Push your branch**:
   ```bash
   git push origin feature-name
   ```
6. **Create a pull request**.

## Outputs 📸

Here are some outputs and screenshots of the app in action:
Home Screen
  
  ![Home 1](https://github.com/user-attachments/assets/c8a5712c-6a14-40bb-bf8e-c33019502b70)
  ![Home 2](https://github.com/user-attachments/assets/e4e4f11e-4578-446c-8053-215d2b938a40)

Contact Us Screen
 
  ![Contract page](https://github.com/user-attachments/assets/a366df74-4184-4197-a311-44e9c924dd08)

About Us Screen
 
  ![About 1](https://github.com/user-attachments/assets/837fcfb7-15d2-4f50-8433-24bece74eafd)
  ![About 2](https://github.com/user-attachments/assets/69a1b01e-9405-46a6-8b2f-a17910593884)

## License 📄
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
