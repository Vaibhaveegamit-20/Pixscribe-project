# Pixscribe-project

Step 1: Run Server
- Open integrated terminal in server
- npm install
- Add the .env file with required details : MONGODB_URI = your-mongodb-uri JWT_SECRET = your-jwt-secret CLIPDROP_API = your-clipdrop-api-key CURRENCY = 'USD' RAZORPAY_KEY_ID=your-razorpay-key-id RAZORPAY_KEY_SECRET=your-razorpay-key-secret
- npm run server

Step 2: Run Client
- Open integrated terminal in Client
- npm install
- Add the .env file with required details: VITE_BACKEND_URL = 'http://localhost:4000' VITE_RAZORPAY_KEY_ID = your razorpay key_id
- npm run dev

The project generates images using AI with just a prompt. Clipdrop API is used to generate images. There is a dark theme toggle which toggles app between light and dark mode. For payment Razorpay is used. User receives a mail regarding account creation and OTP to reset password. Brevo is used to mail configuration.

Test card details for Razorpay Country: US Visa--> 4384 7968 2770 3274, Random CVV, Any future date Mastercard --> 5312 6865 5677 9641, Random CVV, Any future date Amex --> 3782 8224 6310 005, Random CVV, Any future date Diners --> 6594 7300 0000 0001, Random CVV, Any future date
