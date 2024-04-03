# Task Manager (ToDo) App using MERN Stack

Task Manager is a simple todo application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to manage their tasks efficiently.

## Features

- User authentication (signup, login, logout)
- Create, read, update, and delete tasks
- Mark tasks as completed
- Filter tasks by status (completed/incomplete)
- Responsive design for mobile and desktop

## Technologies Used

- **React.js**: A JavaScript library for building user interfaces, used for the frontend.
- **Axios**: A promise-based HTTP client for making requests to the backend API.
- **MongoDB**: A NoSQL database for storing task data and user information.
- **Express.js**: A backend web application framework for Node.js to handle HTTP requests and responses.
- **Node.js**: A JavaScript runtime environment that executes JavaScript code outside of a web browser, used for the backend.
- **JWT (JSON Web Tokens)**: Used for user authentication and authorization.
- **Bcrypt.js**: A library to hash passwords before storing them in the database.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine
- MongoDB Atlas account (or locally installed MongoDB)

### Installation

1. Clone the repository:

```
git clone https://github.com/yourusername/Task-Manager.git
```

2. Navigate to the project directory:

```
cd task-manager
```

3. Install dependencies:

```
npm install
```

4. Create a `.env` file in the root directory and add the following environment variables:

```
PORT=3000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
```

Replace `your_mongodb_uri` with your MongoDB connection string and `your_secret_key` with a secret key for JWT token generation.

5. Start the development server:

```
npm run dev
```

6. Navigate to `http://localhost:3000` in your browser to view the app.
