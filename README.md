# Node.js Authentication Project

This project is a Node.js application that provides authentication functionality, including sign up, sign in, sign out, password reset, and Google login/signup.

## Live Site
Visit the live site [here](https://node-authentication-gpu4.onrender.com/user/signout)


## Environment Variables

To run the application, you need to set the following environment variables in a `.env` file at the root of your project:

1. **PORT**: Specifies the port number the application listens on.
2. **DB_URL**: Specifies the MongoDB database URL.
3. **CLIENT_ID**: Client ID for Google authentication.
4. **CLIENT_SECRET**: Client Secret for Google authentication (sign in with Google).
5. **EMAIL**: Email address to send Gmail messages.
6. **PASSWORD**: Password for the Gmail account (use Gmail App Password if enabled).
7. **RECAPTCHA_SECRET_KEY**: Secret key to use Google reCAPTCHA.
8. **CLIENT_URL**: URL to redirect after signing in with Google, e.g., "http://localhost:3000/auth/login/success".

Ensure that you have the appropriate values for each variable before running the application.

Example `.env` file:

```plaintext
PORT=3000
DB_URL=mongodb://localhost:27017/mydatabase
CLIENT_ID=your_client_id
CLIENT_SECRET=your_client_secret
EMAIL=your_email@gmail.com
PASSWORD=your_gmail_password
RECAPTCHA_SECRET_KEY=your_recaptcha_secret_key
CLIENT_URL=http://localhost:3000/auth/login/success
```

## Folder
  ```csharp
node-authentication/
├── config/                  # Configuration files
│   └── mongodb.js           # MongoDB configuration
│
├── controllers/             # Controller logic
├── models/                  # Database models
├── routes/                  # Route definitions
├── views/                   # EJS views
├── app.js                   # Express application setup
│
├── public/                  # Static assets
│
├── package.json             # NPM package configuration
├── README.md                # Project README file
├── .gitignore               # Git ignore configuration
└── .env                     # Environment variables file

```

## Installation

To run this project locally, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/node-authentication.git
  
2. Navigate to the project directory:
   ```bash
   cd node-authentication
    ```
3. Install dependencies:
   ```bash
   npm install

4. Start the server:
   ```bash
   npm start
- `Open your web browser and visit http://localhost:3000 to access the application.`

## Dependencies

- Express.js
- MongoDB
- Passport.js
- bcrypt
- express-session
- express-ejs-layouts
- dotenv
- nodemailer








  
