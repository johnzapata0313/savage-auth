# Message Board Application

A full-stack message board application built with Node.js, Express, and MongoDB featuring user authentication and interactive voting functionality.

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

## Prerequisites

Before running this project, make sure you have the following installed:

- Node.js (v14 or higher)
- MongoDB (running locally or MongoDB Atlas account)
- npm or yarn

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd <project-directory>
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory with the following variables:
```
PORT=3000
MONGODB_URI=mongodb://localhost:27017/messageboard
SESSION_SECRET=your_secret_key_here
```

4. Start MongoDB (if running locally):
```bash
mongod
```

5. Run the application:
```bash
npm start
```

The application should now be running on `http://localhost:3000`

## Project Structure

```
project/
├── models/
│   ├── User.js
│   └── Message.js
├── routes/
│   ├── auth.js
│   └── messages.js
├── public/
│   ├── css/
│   └── js/
├── views/
│   ├── login.html
│   └── messageboard.html
├── server.js
├── package.json
└── README.md
```

## API Endpoints

### Authentication
- `POST /auth/signup` - Create a new user account
- `POST /auth/login` - Login with existing credentials
- `POST /auth/logout` - Logout current user

### Messages
- `GET /messages` - Retrieve all messages
- `POST /messages` - Create a new message
- `PUT /messages/:id/vote` - Vote on a message (thumbs up/down)

## Usage

1. Navigate to the login page
2. Sign up for a new account or login with existing credentials
3. Post messages to the message board
4. Vote on messages using the thumbs up/down buttons
5. View real-time vote counts

## Testing

Run tests with:
```bash
npm test
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.

## Contact

Your Name - your.email@example.com

Project Link: [https://github.com/yourusername/project-name](https://github.com/yourusername/project-name)
