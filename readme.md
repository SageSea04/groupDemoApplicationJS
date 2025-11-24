### Team Stripe Demo Application

## Description
This is a simple demo application to showcase Stripe payment integration in a web application.
Users can enter a test amount and test card details to simulate payments. This app is built for educational purposes and uses Stripe’s test mode only — no real money is processed.

## Features
- Frontend form to enter payment amount and test card details
- Backend API that creates Stripe Payment Intents
- Displays success or failure messages based on payment status
- Fully functional in Stripe test mode

## Prerequisites
- Node.js (v20.x recommended)
- npm or yarn
- Stripe test API keys

## Installation & Run
1. Clone the repository: git clone https://github.com/SageSea04/groupDemoApplicationJS
2. Install dependencies: npm install
3. Create a `.env` file in the root directory with your Stripe secret key: STRIPE_SECRET_KEY=sk_test_XXXXXXXXXXXXXXXXXXXX
4. Start the backend server: npm start
5. Open the frontend (if separate) or navigate to http://localhost:3000 to access the demo page

## Usage
1. Enter a payment amount (e.g., 5 for $5)
2. Enter any Stripe test card number:
   - Success card: `4242 4242 4242 4242`
                   `4000 0566 5566 5556`
                   `5555 5555 5555 4444`
                   `2223 00312 2003 222`
                   `6011 0009 9013 9424`
   - Declined card: Any combination of numbers
3. Enter expiry, CVC, and ZIP (any valid test values)
4. Click Pay
5. The app will display whether the payment succeeded or failed

## Notes
- All payments are in test mode, no real charges will occur
- Any combination of numbers, expiration dates, CVC codes, and ZIP codes can be used to simulate failed payments

## Optional VS Code Extensions
- ESLint
- Prettier
- Node.js Extension Pack