# Web-App-for-a-bus-Service-Company
# Bus Booking Website

This project allows you to run a basic bus booking website with payment integration, authentication, and backend functionality. The provided code covers essential features such as:

## Features

1. **Backend Server**: Set up using Express.
2. **MongoDB Database**: Connectivity for bus and booking data.
3. **Razorpay Payment Integration**: For online payments.
4. **JWT Authentication**: For user management.
5. **Frontend Form**: To handle booking and payments.
6. **Error Handling and Security Enhancements**: Using libraries like bcrypt for passwords and JWT for token-based authentication.

## Steps to Ensure it Runs Correctly

### 1. Install Dependencies

Make sure you have the following dependencies installed by running:

```bash
npm install express mongoose bcryptjs jsonwebtoken dotenv razorpay
2. Set Up .env File
Create an .env file with the necessary keys:

bash
Copy code
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_SECRET_KEY=your_razorpay_secret_key
3. Start Backend
Use the following command to start the backend server:

bash
Copy code
node server.js
4. Frontend
You can serve the frontend index.html file using Express' static file serving functionality or use an additional tool like live server for local testing.

5. Razorpay Payment
Replace the Razorpay key placeholders with your actual API credentials from Razorpay. Test the payment gateway integration in test mode first.

Testing
Once the website is running:

Test Registration/Login: Ensure you can register a user and log in.
Bus Routes & Booking: Test if the routes and seat numbers are being handled correctly.
Payments: Run a test payment using Razorpay to ensure payment flow is working.
Debugging and Issues
If you encounter errors or issues:

Check the console logs for specific errors.
Ensure MongoDB is running and the connection string in .env is correct.
Ensure the Razorpay API keys are set up properly.
