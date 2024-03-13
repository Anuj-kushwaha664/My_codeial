# Codeial - Social Media App

Codeial is a social media application for tech enthusiasts where users can register, log in, make friends, posts, likes, comments, and chat with Community. This platform is built using EJS, SCSS, Node.js, Express.js, MongoDB, and various Node.js packages such as Nodemailer, Noty, Flash-connect, passportJS and more.

## Features

- **User Registration and Login:** Users can create their account and log in securely using Passport.js and JWT tokens.

- **Profile Management:** Users can update their profile details, including a profile picture, name, bio, and more.

- **Friend Requests:** Users can make friends.

- **Posts and Comments:** Users can create posts, view posts, and leave comments on posts.

- **Likes:** Users can like and unlike posts and comments.

- **Real-time Chat:** Users can chat with community in real time using a chat feature.

## Technologies Used

- **EJS (Embedded JavaScript):** EJS is used for server-side rendering of dynamic web pages.

- **Node.js:** Node.js is the runtime environment used to build the backend server and handle HTTP requests.

- **MongoDB:** MongoDB is the database used to store user data, posts, comments, and other app-related information.

- **Passport.js:** Passport.js is used for user authentication, allowing users to log in securely.

- **JWT Tokens:** JWT (JSON Web Tokens) are used for secure authentication and user sessions.

- **Google OAuth:** Google OAuth is implemented for registration and login using Google accounts.

- **Nodemailer:** Nodemailer is used to send emails for new posts.

- **Noty:** Noty is used to show user-friendly notifications to users.

- **Flash-connect:** Flash-connect is used to display flash messages for user interactions.

## Getting Started

To run Codeial locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Anuj-kushwaha664/My_codeial.git
   cd My_Codeial
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up MongoDB: Make sure you have MongoDB installed and running.

4. Configure Environment Variables: Set up environment variables for MongoDB connection, JWT secret, and other configurations.

5. Start the server:
   ```bash
   npm start
   ```

6. Open your web browser and visit: `http://localhost:8000` to access the Codeial application.

## Contributing

We welcome contributions from the community to improve and enhance Codeial. If you have any suggestions, bug fixes, or new features to add, please submit a pull request. Let's build a better social media experience together!