# Stripe Checkout for Restaurant Cafe

## How to Use

This free, open-source Stripe Payment Link Generator demo is designed for restaurants, cafes, and delivery services looking for a simple and secure way to create payment links. Follow these steps to get started quickly:

### Configuration

- **Set Stripe API Keys:**  
  Open your `.env` file and define your Stripe Publishable and Secret keys:  
STRIPE_API_KEY=
PAYMENT_FLAVOR_TEXT=


- **Set Database Credentials:**  
Update your database connection settings in `server.js` to match your MySQL server.

- **Prepare the Database:**  
Create a new database named `stripe_db`. Then import the provided `stripe_db.txt` file into your database using phpMyAdmin or the MySQL command line.

- **Set Stripe API Key for Node.js:**  
Place your Stripe API key (test or live) in the `.env` file.

---

## Installation (Node.js)

1. **Unzip the Package:**  
 Extract the contents of `Stripe-Checkout-for-Restaurant-Cafe-main.zip` to your working directory.

2. **Navigate to Project Folder:**  

 cd stripecheckout
Install Dependencies:

npm install
npm install mysql2
Update Database Settings:
Edit server.js to configure your MySQL database credentials.

Restore Database:
Import stripe_db.txt into your MySQL server (using phpMyAdmin or command line).

Run the Server:

node server.js
Access the App:
Open your browser and go to http://localhost:4242.

Features (Demo Version):
Instantly generate secure Stripe payment links
Built-in tipping support (fixed amount or percentage)
Multi-language interface (English, Portuguese, Russian, Ukrainian)
Clean, responsive design for all device sizes
Easy-to-use admin dashboard for managing payments and settings

For custom Stripe Checkout or PaymentIntent integration, feel free to reach out!
