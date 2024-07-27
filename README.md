
# Twitter-like Social Media Platform

A full-stack social media platform inspired by Twitter, developed and deployed using the MERN stack (MongoDB, Express.js, React.js, Node.js).

## Features

### Frontend (React.js)
1. **User Authentication:**
   - Sign-up and login functionality.
   - JWT-based authentication.
2. **User Profile:**
   - View and edit user profile information.
   - Follow and unfollow other users.
3. **Tweet Management:**
   - Create, edit, and delete tweets.
   - Display timeline of tweets from followed users.
4. **Real-time Updates:**
   - Real-time notifications for new tweets and followers.
5. **Responsive Design:**
   - Mobile-friendly interface for accessing the platform on various devices.

### Backend (Node.js, Express.js)
1. **RESTful API:**
   - CRUD operations for users and tweets.
   - Authentication and authorization using JWT.
2. **WebSocket Integration:**
   - Real-time updates and notifications.
3. **Database Management:**
   - MongoDB for storing user and tweet data.
   - Mongoose for schema definitions and data validation.

### Database (MongoDB)
1. **Schemas:**
   - **User Schema:** Username, email, password, profile information, followers, following.
   - **Tweet Schema:** Content, author, timestamp, likes, retweets.

### Additional Features
1. **Security:**
   - Password hashing using Bcrypt.
   - Secure API endpoints with JWT authentication.
2. **Search Functionality:**
   - Search users and tweets.
3. **Responsive Design:**
   - Ensures usability on various devices, including mobile and desktop.

### Tools and Libraries
- **Frontend:**
  - React.js for building the user interface.
  - Redux for state management.
  - Axios for API calls.
- **Backend:**
  - Node.js and Express.js for building the API.
  - Mongoose for interacting with MongoDB.
  - Bcrypt for password hashing.
  - JWT for secure token-based authentication.
  - WebSocket for real-time updates.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/twitter-like-platform.git
   ```
2. **Install dependencies for the backend:**
   ```bash
   cd twitter-like-platform/backend
   npm install
   ```
3. **Install dependencies for the frontend:**
   ```bash
   cd ../frontend
   npm install
   ```

## Usage

### Setup .env file

```js
MONGO_URI=...
PORT=...
JWT_SECRET=...
NODE_ENV=...
CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...
```

1. **Run the backend server:**
   ```bash
   cd backend
   npm start
   ```
2. **Run the frontend server:**
   ```bash
   cd frontend
   npm start
   ```

3. **Open the application:**
   Open your browser and navigate to `http://localhost:3000`
