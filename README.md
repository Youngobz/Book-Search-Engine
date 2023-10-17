# Book-Search-Engine

A MERN (MongoDB, Express.js, React, Node.js) stack application that allows users to search for books and save their favorites. The application integrates with the Google Books API to fetch book details.

## 🌟 Features

- **User Authentication**: Secure user registration and login functionality.
- **Book Search**: Utilizes the Google Books API to allow users to search for books by title, author, or keywords.
- **Save Books**: Users can save their favorite books with a single click.
- **View Saved Books**: Access and manage a list of saved books in the user profile.
- **Delete Saved Books**: Option to remove books from the saved list.

## 📂 Directory Structure

- `client`: Frontend React application.
  - `src`: Source files for the React app.
    - `components`: Reusable UI components.
    - `pages`: Main application views.
    - `utils`: Utility functions, API calls, and authentication methods.
- `server`: Backend Express server.
  - `config`: Database connection setup.
  - `controllers`: Logic for API route handling.
  - `models`: Mongoose models for MongoDB.
  - `routes`: API route definitions.
  - `schema`: GraphQL type definitions and resolvers.

## 🚀 Getting Started

### Prerequisites

- Node.js and npm installed.
- MongoDB running on your machine.

### Installation

1. Clone the repository: `git clone https://github.com/Youngobz/Book-Search-Engine.git`
2. Navigate to the project directory: `cd Book-Search-Engine`
3. Install main dependencies: `npm install`
4. Navigate to the `client` directory and install client-side dependencies: `cd client && npm install`
5. Navigate to the `server` directory and install server-side dependencies: `cd ../server && npm install`
6. Create a `.env` file in the `server` directory with your MongoDB connection string and JWT secret.

### Running the Application

- From the root directory, run both client and server: `npm run develop`
- To run only the server, navigate to the `server` directory: `cd server && npm start`

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, make changes, and submit pull requests. Let's collaborate and make this application even better!

## 📜 License

This project is open-source. Please refer to the repository's license file for more details.