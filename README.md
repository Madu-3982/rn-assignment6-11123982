### Overview
This is a simple e-commerce mobile application built using React Native. It allows users to view a list of products, add them to a cart, and proceed to checkout.

### Features
Home Screen: Displays a grid of available products with images, names, and prices.
Checkout Screen: Shows selected products with a remove option, total price, and checkout button.
Data Storage: Utilizes AsyncStorage for local storage of the cart items.
### Design Choices
Navigation: Implemented using React Navigation for seamless navigation between Home and Checkout screens.
Styling: Used StyleSheet from React Native for consistent styling across components.
State Management: Managed cart state using React's useState hook and AsyncStorage for persistent storage.
UI Components: Employed FlatList for efficient rendering of product lists and Image for displaying product images.
Icons: Included icons for various functionalities like adding to cart, removing items, and navigation.
### Implementation of Data Storage
AsyncStorage: Used AsyncStorage from '@react-native-async-storage/async-storage' to store the cart items locally on the device.
Loading Cart: Upon loading the app, useEffect hook retrieves the stored cart items and updates the state if present.
Adding and Removing Items: Implemented functions to add products to the cart and update AsyncStorage accordingly. Removal functionality also updates the cart state and storage.
### Screenshots

Figure 1: Home Screen displaying product grid.
\assets\Screenshot 1.jpeg
Figure 2: Checkout Screen showing selected items and total price.
\assets\Screebshot2.jpeg

### Installation
Clone the repository.
Install dependencies using npm install.
Run the app using npm start or expo start.
### Dependencies
React Native
React Navigation
AsyncStorage

### Future Improvements
Implement user authentication and user-specific carts.
Enhance UI/UX with animations and better styling.
Add more features like product search and filtering.