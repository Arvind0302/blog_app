# Blog App

A full-featured blog application built with Node.js, Express, and MongoDB.

## Features

- User authentication and authorization
- Create, read, update, and delete blog posts
- Comment system
- Responsive design
- Flash messages for user feedback

## Prerequisites

- Node.js (v12 or higher)
- MongoDB (local or Atlas)

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd blog_app
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add the following variables:
```
MONGODB_URI=your_mongodb_connection_string
SESSION_SECRET=your_session_secret
PORT=3000
```

4. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:3000`

## Scripts

- `npm start`: Start the production server
- `npm run dev`: Start the development server with nodemon

## Technologies Used

- Node.js
- Express.js
- MongoDB with Mongoose
- EJS templating
- Passport.js for authentication
- Bootstrap for styling

## License

ISC 