# Project Title

## Description

This is a MEAN stack application that provides a user management system. It allows users to create, read, update, and delete user information.

## Features

- User registration and authentication
- User profile management
- Responsive design using Angular Material
- RESTful API for backend operations

## Installation

## Environment Variables

Create a `.env` file in the root of the backend directory and add the following variables:

```bash
MONGODB_URI=<your_mongodb_connection_string>
JWT_SECRET=<your_jwt_secret>
```

Make sure to replace `<your_mongodb_connection_string>` and `<your_jwt_secret>` with your actual MongoDB connection string and JWT secret.

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the backend directory and install dependencies:

   ```bash
   cd backend
   npm install
   ```

3. Navigate to the frontend directory and install dependencies:

   ```bash
   cd frontend
   npm install
   ```

## Usage

1. Start the backend server:

   ```bash
   cd backend
   node app.js
   ```

2. Start the frontend application:

   ```bash
   cd frontend
   ng serve
   ```

3. Open your browser and navigate to `http://localhost:4200` to access the application.

## Technologies Used

- MongoDB
- Express.js
- Angular
- Node.js
- Angular Material

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or features.

## License

This project is licensed under the MIT License.
