# Savage Auth Fullstack App

A full-stack message board application built with Node.js, Express, and MongoDB featuring user authentication and interactive voting functionality, in honor of the great 21 Savage.

![132ACCB1-500E-4834-A247-612184CCD2E8](https://github.com/user-attachments/assets/73127266-6030-43b0-91b9-9a0f25efde6c)

https://savage-auth-b4ft.onrender.com

## Features

- **User Authentication**: Secure sign-up and login system
- **Message Board**: Post and view messages from all users
- **Voting System**: Thumbs up and down voting on messages
- **Session Management**: Persistent user sessions

## Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: Express-session, bcrypt (or similar)
- **Frontend**: HTML, CSS, JavaScript

## Lessons Learned

This project reinforced critical full-stack development skills including proper database connection timing (starting the Express server only after MongoDB connects), environment-specific configuration using `process.env` variables, and MongoDB ObjectId conversion for CRUD operations. Key challenges included debugging the GitHub-to-Render deployment pipeline, configuring MongoDB Atlas IP whitelisting for production access, resolving Git merge conflicts, and implementing complete CRUD functionality with proper error handling. The experience emphasized the importance of reading deployment logs to diagnose issues, understanding the request-response cycle, and managing asynchronous database operations before route initialization.



