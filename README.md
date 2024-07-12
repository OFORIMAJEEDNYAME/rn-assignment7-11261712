### rn-assignment7-11261712
###App
This React Native project showcases a fashion store app with a variety of functionalities, including product listing, detailed views of individual products, and cart management. It incorporates navigation through stack and drawer navigators and includes persistent storage with AsyncStorage for the cart feature.

###Table of Contents
Fashion App
Table of Contents
Features
Prerequisites
Installation
Usage
Components
Screens
Navigation
Styles
API

###Features
Display a list of products fetched from an API
Detailed view of individual products
Add products to a cart using AsyncStorage
Drawer navigation for easy access to different sections
Header and drawer UI components for a better user experience

###Prerequisites
Node.js
npm or yarn
React Native CLI or Expo CLI

###Installation
Clone the repository:
bash
Navigate to the project directory:
bash
cd App
Install dependencies:
bash
npm install
###Usage
Start the development server:
bash

Use the app on your connected device or emulator.

###Components
Drawer
The Drawer component provides the navigation drawer for the app.
Props:
isOpen: Boolean indicating whether the drawer is open.
onClose: Function to close the drawer.
Header
The Header component renders the header with a logo and search icon.

###Screens
HomeScreen
Fetches and displays a list of products.
Allows navigation to the ProductDetail screen.
Provides functionality to add products to the cart.

ProductDetailScreen
Displays detailed information about a selected product.
Allows adding the product to the cart.
CartScreen
Displays the products added to the cart.
Allows removing products from the cart.

###Navigation
The app uses React Navigation for navigation management. It includes:

createStackNavigator for stack navigation.
createDrawerNavigator for drawer navigation.
Navigation Configuration:

###HomeStack: Stack navigator for home and product detail screens.
App: Main component including drawer navigation for home and cart screens.
Styles
The app uses React Native's StyleSheet for styling components.

###API
The app fetches product data from the Fake Store API.
###ScreenShot
![Screenshot 2024-07-12 203110](https://github.com/user-attachments/assets/d138de9f-8ac1-4451-a972-5748060d48e7)
![Screenshot 2024-07-12 203228](https://github.com/user-attachments/assets/baeb8c71-e6d8-43f0-8b4a-97abc03958e2)
![Screenshot 2024-07-12 203110](https://github.com/user-attachments/assets/3bb7ba6d-6e0d-4b0d-9109-cc9aff37370d)


