# Knowtify

Knowtify is a web app tailored for college environments, enabling college staff, seniors, and batch-mates to post notifications and posts for various activities. The platform includes a low latency chat facility, upvoting system for posts, and a discussion section under each user post.

## Features

- Notification/Posts: College staff, seniors, and batch-mates can post notifications or posts for various activities.
- Chat Facility: Low latency chat between users on the platform using Socket.io.
- Upvoting System: Users can upvote a post, which increases the weight of different posts.
- Discussion Section: Supports discussions under user posts where viewers can ask questions and engage further.

## Tech Stack

- Frontend: React.js, Chakra UI, Socket.io
- Backend: Node.js, Express.js, JWT Authentication
- Database and Cloud Storage: MongoDB, Cloudinary

## Installation and Setup

### Prerequisites

- Node.js
- npm (Node Package Manager)
- MongoDB account
- Cloudinary account

### Steps to run the project

1. Clone the repository:
   ```
   git clone https://github.com/yash037/Knowtify.git
   cd knowtify
   ```
2. Install dependencies for both frontend and backend:
   ```
   cd backend
   npm install
   cd ../knowtify
   npm install
   ```
3. Build the project:
   ```
   cd backend
   npm run build
   cd ../knowtify
   npm run build
   ```
4. Add .env file in the backend folder with the following format:
   ```
   PORT=
   MONGO_URI=
   JWT_SECRET=
   CLOUDINARY_CLOUD_NAME=
   CLOUDINARY_API_KEY=
   CLOUDINARY_API_SECRET=
   ```
5. Start the development server:
   ```
   cd backend
   npm start
   cd ../knowtify
   npm start
   ```

## Usage
- After completing the setup, you can start using Knowtify. College staff, seniors, and batch-mates can post notifications and interact with each other through the chat facility. Users can upvote posts to increase their visibility and engage in discussions under each post.

## Acknowledgments
Special thanks to the developers and maintainers of the libraries and tools used in this project.
