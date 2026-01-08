# Stripe Payment Link Generator– Node.js Demo

Free open-source demo version of a simple and secure Stripe payment link generator, perfect for restaurants, cafes, and delivery services.

### Features (Demo Version)
- Instant secure Stripe payment links
- Built-in tip support (fixed amount or percentage)
- Multi-language interface: English, Portuguese, Russian, Ukrainian
- Clean and responsive design
- Live demo: [https://tomiktmk.com/](https://tomiktmk.com/)

### Live Demo
Try it now: [https://tomiktmk.com/](https://tomiktmk.com/)

### Admin Dashboard
define('STRIPE_PUBLISHABLE_KEY', 'your_keys_here');
define('STRIPE_SECRET_KEY', 'your_keys_here');
Set database credentials in config.php
Set Stripe API keys in config.php

### DB
Create DB stripe_db 
Import TABLE from stripe_db.txt with phpmyadmin or by command line

### Stripe API
Set Stripe API Key in .env file ( Stripe Testing or Live )

### Installation (Node.js)
```bash
git clone https://github.com/4webhub/Stripe-Checkout-for-Restaurant-Cafe.git
cd Stripe-Checkout-for-Restaurant-Cafe
unzip stripecheckout.zip
cd stripecheckout
npm install
npm install mysql2
node server.js

visit localhost:4242

For any custom Stripe Checkout or Stripe PaymentIntent code, please feel free to contact me.
