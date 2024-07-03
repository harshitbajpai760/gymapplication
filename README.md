# gymapplication

## Project Overview

gym application is a modern real estate platform built using the MERN stack. It offers users the ability to browse, list, and manage property listings with an integrated authentication system. The project incorporates user authentication  and Google authentication using Firebase.

## Authors
   **Training project (Batch-4)**
   **(Course: BCA 4th semester)**

- **Harshit bajpai**
  - Roll Number: 22015002278
- **Aradhya singh**
  - Roll Number: 22015002255
- **Arjun dutta**
  - Roll Number: 22015002256

## Features

- User authentication 
- Google authentication via Firebase
- Create, read, update, and delete property listings
- Responsive and user-friendly UI
- State management with Redux Toolkit

## Technology Stack

- **Frontend:**
  - React-VITE
  - Redux Toolkit
  - CSS 
  - Tailwind CSS
  
  

- **Backend:**
  - Node.js
  - Express.js

- **Database:**
  - MongoDB

- **Authentication:**
  - Firebase (Google Auth)
  - Custom User Authentication (JWT)

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js
- npm or yarn
- MongoDB
- Firebase account

### Installation


2. Install the dependencies for both the client and server:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```

3. Set up environment variables:

   Create a `.env` file in the `server` directory and add your MongoDB URI and JWT secret:

   ```plaintext
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   ```

   Create a `.env` file in the `client` directory and add your Firebase configuration:

   ```plaintext
   REACT_APP_FIREBASE_API_KEY=your_api_key
   REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
   REACT_APP_FIREBASE_PROJECT_ID=your_project_id
   REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
   REACT_APP_FIREBASE_APP_ID=your_app_id
   ```

### Running the Application

1. Start the backend server:
   ```bash
   cd server
   npm start
   ```

2. Start the frontend development server:
   ```bash
   cd client
   npm start
   ```

3. Open your browser and navigate to `http://localhost:3000` to see the application in action.

## Contributing

We welcome contributions to gym application! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request



---


  
