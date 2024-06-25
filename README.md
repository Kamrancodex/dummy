# Wallet Management System

Welcome to the Wallet Management System! This project is a comprehensive web application designed to manage user wallets, perform transactions, and handle various financial operations seamlessly.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

### Frontend Features

1. **User Authentication:**

   - Sign Up: Create a new account.
   - Sign In: Log into an existing account.
   - Sign Out: Log out from the account.
   - Forgot Password: Reset the password via email.
   - Email Verification: Verify user email addresses with OTP.

2. **Dashboard:**

   - Overview of account balance and recent transactions.
   - Graphical representation of income and expenses.
   - Notifications and messages display.

3. **Wallet Management:**

   - View total balance, mortgage, and expected amounts.
   - Transfer money to other users.
   - Request money from other users.
   - Currency conversion support.

4. **Card Management:**

   - Apply for credit cards.
   - Add and manage debit cards.
   - View card details and transaction history.
   - Toggle visibility of sensitive card information.

5. **Profile Management:**

   - View and update personal information.
   - Change password.
   - Update address.
   - Upload and change profile pictures.
   - Two-factor authentication via email and phone.

6. **Transaction Management:**

   - View detailed transaction history.
   - Filter transactions by date and type.
   - Export transaction history.

7. **Notifications:**

   - Real-time toast notifications for various events (e.g., successful login, transaction alerts).

8. **Responsive Design:**
   - Fully responsive layout compatible with desktop, tablet, and mobile devices.

## Tech Stack

### Frontend

- **React:** JavaScript library for building user interfaces.
- **React Router:** Declarative routing for React applications.
- **Tailwind CSS:** Utility-first CSS framework for rapid UI development.
- **Axios:** Promise-based HTTP client for the browser and Node.js.
- **React Toastify:** Library for toast notifications.
- **React Icons:** Comprehensive set of icons for React.

### Backend (Once Connected)

- **Node.js:** JavaScript runtime built on Chrome's V8 JavaScript engine.
- **Express:** Fast, unopinionated, minimalist web framework for Node.js.
- **MongoDB:** NoSQL database for storing user and transaction data.
- **Mongoose:** Elegant MongoDB object modeling for Node.js.
- **JWT (JSON Web Tokens):** For secure authentication.
- **Nodemailer:** Module for Node.js applications to send emails.
- **Stripe API:** For handling payment processing.

## Installation

### Prerequisites

- Node.js and npm installed on your local machine.

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/wallet-frontend.git
   cd wallet-management-system
   ```
   Install dependencies:

bash
Copy code

```
npm install
```

2. **Create a .env file in the root directory and add the necessary
   environment variables**: env Copy code

````
REACT_APP_API_URL=http://localhost:8000/api/v1 ```

3. **Start the development server**:
bash Copy code

````

npm run dev ```

### Usage

- **User Authentication**

  - Sign Up
  - Sign In
  - Forgot Password
  - Reset Password
  - Email and Phone Number Verification

- **Dashboard**

  - Overview of user account
  - Recent transactions
  - Balance summary

- **Profile Management**

  - View and update personal information
  - Upload profile picture
  - Change password
  - Verify email and phone number

- **Cards Management**

  - View credit and debit cards
  - Apply for a new credit card
  - Add a new debit card
  - View card details securely

- **Transactions**

  - View transaction history
  - Filter transactions by date, type, and status

- **Payments**

  - Send money to other users
  - Request money from other users
  - Pay using email or phone number
  - Scan and pay using QR code

- **KYC Verification**
  - Submit documents for KYC verification
  - Track KYC status

### Future Features

- **Cryptocurrency Integration**
  - **Pay with Crypto**
    - Users can pay using cryptocurrencies.
    - Crypto will be swapped first and then the payment will be processed.
  - **Crypto Buying**
    - Users can buy cryptocurrencies within the wallet.
  - **Crypto Swaps**
    - Swap one cryptocurrency for another seamlessly.
  - **Crypto Payments to Wallets and Banks**
    - Pay directly to any wallet or bank using cryptocurrencies.
  - **Real-time Exchange Rates**
    - Display real-time crypto exchange rates for accurate transactions.

## Tech Stack

- **Frontend**

  - React.js
  - Tailwind CSS
  - Axios for API calls
  - React Router for navigation
  - React Toastify for notifications
  - JWT for authentication

- **Backend**
  - Node.js
  - Express.js
  - MongoDB with Mongoose
  - JWT for authentication
  - Nodemailer for sending emails
  - Axios for external API calls (e.g., exchange rates)

### Contributing We welcome

contributions to the Wallet Management System. Please follow these steps to
contribute: Fork the repository. Create a new branch for your feature or bugfix.
Make your changes and commit them. Push your changes to your fork. Open a pull
request to the main repository. License This project is licensed under the MIT
License. See the LICENSE file for more details. Contact If you have any
questions or suggestions, feel free to reach out: Email: your-email@example.com
GitHub: yourusername javascript Copy code Replace the placeholders (e.g.,
`yourusername`, `your-email@example.com`, etc.) with your actual information.
Once y

i will be adding more features to this project i have many ideas like somehow incorporating crypto and pay with crypto feature

```

```
