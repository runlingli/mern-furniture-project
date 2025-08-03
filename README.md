# MERN Furniture Project

A simple MERN (MongoDB, Express, React, Node.js) stack project for learning and practicing full-stack web development.

## Features

- Product CRUD (Create, Read, Update, Delete)
- Zustand for React state management
- Chakra UI for modern React components
- RESTful API with Express and MongoDB

## Project Structure

```
mern-crash-course/
├── backend/         # Node.js + Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/        # React frontend (with Chakra UI & Zustand)
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── store/
│   └── package.json
├── package.json     # Root scripts for dev/build/start
└── README.md
```

## Getting Started

### 1. Install dependencies

```sh
npm run build
```

### 2. Development

- **Backend:**  
  Start the backend server:
  ```sh
  npm run dev
  ```
- **Frontend:**  
  In a separate terminal, start the frontend dev server:
  ```sh
  cd frontend
  npm run dev
  ```

### 3. Production Build

```sh
npm run build
npm run start
```

- This will build the frontend and serve it with the backend on the same port.

## Environment Variables

Create a `.env` file in the `backend` folder for your MongoDB URI and other configs:

```
MONGO_URI=your_mongodb_connection_string
PORT=5000
```
