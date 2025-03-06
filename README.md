# Recipe Finder

The **Recipe Finder** is a web application designed to help users discover and upload recipes, manage meal plans, and explore various cuisines with multilingual support.

## Features

- **Authentication**
  - Google sign-in via Firebase Authentication.

- **Dynamic Recipe Display**
  - Recipes are fetched and displayed dynamically in a responsive grid layout.
  - Filters available for category, preparation time, and dietary preferences.

- **Dark Mode**
  - Toggle between light and dark themes.

- **Multilingual Support**
  - Interface available in multiple languages (English, Spanish).

- **Responsive Design**
  - Optimized for desktop and mobile devices.

## Technologies Used

- **Frontend:** HTML, CSS (embedded), JavaScript (ES6)
- **Backend:** Firebase Realtime Database, Firebase Storage
- **Authentication:** Firebase Authentication (Google Sign-In)

## Firebase Configuration

Ensure the following Firebase services are set up:
1. Authentication
2. Realtime Database
3. Storage
4. Hosting (if deploying)

Add the Firebase configuration object to the script:
```javascript
const firebaseConfig = {
  apiKey: "AIzaSyCvv051YiSoYeO81kKWIS4_gDQBALQTsxQ",
  authDomain: "recipe-finder-55ca8.firebaseapp.com",
  projectId: "recipe-finder-55ca8",
  storageBucket: "recipe-finder-55ca8.firebasestorage.app",
  messagingSenderId: "1012815961301",
  appId: "1:1012815961301:web:7a363706c3ab2705f4565c",
  measurementId: "G-HHXRQJJKC3"
};
