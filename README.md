# 🛍️ Shopping App

## Features

- 🔐 **Sign In & Sign Up:** Users can create an account or log in to their existing accounts using Firebase Authentication.
- 🛍️ **Product Listing:** View available products with details and images.
- ➕ **Add to Cart:** Users can add products to their cart for easy purchase.
- ➖ **Remove from Cart:** Users can remove items from their cart.
- ✅ **Place Order:** Users can complete their purchases securely.
- 📜 **Order History:** Users can view their previous orders and details.
- 🔍 **Filters:** Filter products based on categories, price, etc.
- 🔎 **Search Option:** Quickly search for products by name.

## Tech Stack

- **Frontend:** ReactJS, Redux, React Router
- **Backend:** Firebase (Firestore, Authentication)
- **State Management:** Redux
- **Styling:** CSS (or any CSS framework you prefer)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/shopping-app.git
   cd shopping-app
Install the dependencies:

bash
Copy code
npm install
Set up Firebase:

Create a Firebase project at Firebase Console.

Enable Firestore and Authentication (Email/Password).

Get your Firebase configuration and add it to your project in a .env file:

env
Copy code
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
Start the development server:

bash
Copy code
npm start
Open your browser and navigate to http://localhost:3000.
