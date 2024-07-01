# Next.js & NestJS Tree Management Application

This full-stack application demonstrates a robust tree structure management system with a depth of up to 10,000 nodes. It uses Next.js for the frontend and NestJS for the backend, showcasing efficient state management and performance optimization techniques.

## Key Features:
- User authentication system
- Interactive tree structure with 10,000 node depth capability
- Real-time node value updates with propagation
- Efficient state management
- Backend API for saving and retrieving tree structures
- Performance-optimized for handling large data structures

## Tech Stack:
- Frontend: Next.js, React
- Backend: NestJS
- Database: MongoDB
- State Management: Context API

## Project Structure:
- `/frontend`: Next.js application
- `/backend`: NestJS application

## Getting Started:
  ### Prerequisites
  - Node.js (v14.0.0 or later)
  - npm (v6.0.0 or later)
  - Git
  - MongoDB
  ### Installation
  1. Clone the repository:
    git clone https://github.com/Dhanashree-Chandratre/Deep-Tree-Implementation-with-Next.js-and-NestJS.git
    cd Deep-Tree-Implementation-with-Next.js-and-NestJS
  2. Set up the backend:
    cd tree-management-backend
    npm install
  3. Set up the frontend:
    cd ../tree-management-frontend
    npm install
  4. Set up environment variables
- In the backend directory, create a `.env` file and add your database connection string and other necessary variables:
  ```
  DATABASE_URL=your_database_connection_string
  JWT_SECRET=your_jwt_secret
  ```
- In the frontend directory, create a `.env.local` file and add:
  ```
  NEXT_PUBLIC_API_URL=http://localhost:3000/api
  ```

5. Start the development servers
- For the backend:
  ```
  cd tree-management-backend
  npm run start:dev
  ```
- For the frontend (in a new terminal):
  ```
  cd tree-management-frontend
  npm run dev
  ```

6. Open your browser and navigate to `http://localhost:3000` to see the application running.

### Running Tests

- To run backend tests:
cd tree-management-backend
npm run test

- To run frontend tests:
cd frontend
npm run test

## Contributor:
Dhanashree-Chandratre
