# Instagram Clone - React Native CLI

An Instagram-inspired mobile application built using **React Native CLI** and **Firebase**, offering essential features like user authentication, image uploads, post interactions, and more.

---

## Features

### User Authentication
- Firebase-based **Sign Up**, **Log In**, and **Sign Out**.
- Secure user data managed with Firebase Authentication and Firestore.

### Firebase Integration
- Real-time database for handling user data and posts.
- Firebase Storage for seamless image uploading and fetching.

### Redux State Management
- **Global state management** using Redux.
- Real-time updates with Firebase subscribers.

### Post Interactions
- Add posts with images.
- Like/dislike functionality with database updates.

### Dynamic UI
- Custom headers and reusable UI components.
- Fully responsive design for optimal user experience.

### Image Uploading
- Upload images directly from your device to Firebase Storage.

---

## Tech Stack
- **React Native CLI**
- **Firebase** (Authentication, Firestore, Storage)
- **Redux**
- **JavaScript (ES6+)**

---

## Installation

### Prerequisites
Ensure the following tools are installed on your system:
- Node.js
- React Native CLI
- Android Studio or Xcode

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/FirojAhmad1999/Instagram-Clone---React-Native-CLI.git
   cd instagram-clone

Install dependencies:

bash
Copy code
npm install
Set up Firebase:

Create a project in the Firebase Console.
Add the configuration to a file named firebaseConfig.js in your project:
javascript
Copy code
export const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID",
};
Link native dependencies:

bash
Copy code
npx react-native link
Start the Metro Bundler:

bash
Copy code
npx react-native start
Run the application:

For Android:
bash
Copy code
npx react-native run-android
For iOS:
bash
Copy code
npx react-native run-ios
Project Structure
plaintext
Copy code
src/
├── action/
├── assets/
│   └── undraw_welcome_component.svg
├── components/
│   ├── EmptyContainer.js
│   └── Post.js
├── layout/
│   └── CustomHeader.js
├── reducer/
│   ├── auth.js
│   ├── index.js
│   └── post.js
├── screens/
│   ├── AddPost.js
│   ├── Home.js
│   ├── SignIn.js
│   └── SignUp.js
├── utils/
│   ├── AskPermission.js
│   └── options.js
├── App.js
├── RootApp.js
└── store.js
Additional Project Files
.buckconfig: Configuration for the Buck build system.
.eslintrc.js: Linting configuration for code quality.
flowconfig: Configuration for Flow, a static type checker.
Features in Detail
Authentication
Create and log in with user credentials.
Firebase Authentication ensures secure user sessions.
Posts
Users can create, like, and dislike posts.
Real-time updates across all users.
Image Upload
Upload images directly from your device to Firebase Storage.
State Management
Efficient state management using Redux.
Contributions
Contributions are welcome!
Feel free to fork this repository and submit a pull request.

License
This project is licensed under the MIT License.

Author
Firoj Ahmad






