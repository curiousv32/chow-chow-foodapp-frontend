# Chow Chow Food Ordering App

Welcome to the **Chow Chow Food Ordering App**! This application provides a seamless experience for managing restaurants and placing orders online. Below you will find instructions on how to set up and use the app, including how to simulate the app’s functionality.

## Overview

The Chow Chow app consists of a **frontend** and a **backend**:

- **Frontend:** Built with [React](https://reactjs.org/) and hosted on [Render](https://render.com/)
- **Backend:** Built with [Express](https://expressjs.com/) and [Stripe](https://stripe.com/), hosted on [Render](https://render.com/)

The app allows users to create and manage restaurants, place orders, and process payments via Stripe. 

## Live Application

You can try out the live application here: [Chow Chow Live App](https://chow-chow-foodapp-frontend.onrender.com/)

## How to Simulate the App

### 1. **Create an Account (Restaurant Owner)**

1. Open an **incognito** or **private browsing** window.
2. Navigate to the **Chow Chow Food Ordering App**: [Chow Chow Live App](https://chow-chow-foodapp-frontend.onrender.com/)
3. **Sign Up** as a new user (Restaurant Owner).
4. After logging in, go to the **Manage Restaurant** section.
5. Input the details for a new restaurant and click **Save**.

### 2. **Place an Order (Customer)**

1. Open a **regular browser** window.
2. Log in as a **user** (if you don’t have an account, you can sign up as a new user).
3. Navigate to the **Home Page**.
4. Search for the restaurant you created in the incognito window.
5. Place an order for that restaurant.
6. You will be redirected to Stripe for payment processing.

   - **Test Card Number:** `4242 4242 4242 4242`
   - **Expiry Date:** Any future date
   - **CVC:** Any 3 digits

### 3. **Order Management**

1. Return to the **incognito window** where you are logged in as the Restaurant Owner.
2. Go to the **Orders** section.
3. Change the status of the order you placed in the regular browser (e.g., from "Pending" to "Delivered").
4. The status update will be reflected in the regular browser where the customer placed the order.

## Features

- **Restaurant Management:** Add, edit, and delete restaurant details.
- **Order Placement:** Users can place orders and pay using Stripe.
- **Order Tracking:** Restaurant owners can update the status of orders, which is reflected in real-time.

## Technologies Used

- **Frontend:** React, React Router
- **Backend:** Node.js, Express, Stripe
- **Database:** MongoDB (optional)

## Setup and Installation

### Backend

1. Clone the backend repository:
   ```bash
   git clone https://github.com/your-username/chow-chow-backend.git
   ```
2. Navigate to the project directory:
   ```bash
   cd chow-chow-backend
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up environment variables in a `.env` file with the required keys (refer to `.env.example` for the format).
5. Start the backend server:
   ```bash
   npm start
   ```

### Frontend

1. Clone the frontend repository:
   ```bash
   git clone https://github.com/your-username/chow-chow-frontend.git
   ```
2. Navigate to the project directory:
   ```bash
   cd chow-chow-frontend
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the frontend development server:
   ```bash
   npm start
   ```

## Contributing

Feel free to fork the repository and submit pull requests. Please ensure that you follow the code style guidelines and include tests for new features.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any questions or issues, please contact [cuuriousv32@gmail.com](mailto:curiousv32@gmail.com).

