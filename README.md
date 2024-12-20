# Jot-it-Down

**Jot-it-Down** is a full-stack web application that allows users to create, manage, and organize notes. It is built using a **frontend** (client-side) application and a **backend** (server-side) application, both integrated to provide a seamless user experience.

This repository serves as a unified workspace for both the backend and frontend components of the project.

## Key Features:
- **Create Notes**: Users can create and save notes for personal use.
- **View Notes**: Display a list of saved notes with options to edit and delete.
- **User Authentication**: Secure user registration and login system for personalized note-taking.
- **Search and Filter**: Easily search and filter notes based on keywords.

## Link to Frontend Repo
The frontend is built using **React** to create a dynamic and responsive user interface.

[Frontend Repo](https://github.com/katkhedepushpak/notes-app-frontend)

### Key Technologies Used in Frontend:
- **React**: A JavaScript library for building user interfaces.
- **Redux**: For state management across the application.
- **Axios**: For making HTTP requests to the backend.
- **HTML/CSS**: For structuring and styling the application.
- **Bootstrap/Material UI**: For UI components and responsive design.

## Link to Backend Repo
The backend is powered by **Node.js** and **Express** to provide a robust API for handling user authentication, note creation, and data storage.

[Backend Repo](https://github.com/katkhedepushpak/notes-app-backend)

### Key Technologies Used in Backend:
- **Node.js**: A runtime environment for executing JavaScript on the server side.
- **Express**: A web application framework for Node.js that simplifies API routing.
- **MongoDB**: A NoSQL database to store user notes and authentication data.
- **JWT (JSON Web Token)**: For secure user authentication and authorization.
- **Bcrypt**: For hashing passwords securely.
- **Mongoose**: For interacting with MongoDB in a more structured way.

## How It Works:
- **Frontend**: The frontend is a React-based web app that interacts with the backend API. It allows users to register, log in, and manage their notes. The frontend sends HTTP requests (GET, POST, PUT, DELETE) to the backend to perform CRUD operations (Create, Read, Update, Delete).
- **Backend**: The backend exposes a set of RESTful API endpoints to manage notes and handle user authentication. It processes incoming requests from the frontend, performs necessary operations, and sends responses back to the client. The backend also manages user sessions using JWT for secure access.

### Clone the Repositories:
Clone both the frontend and backend repositories:

```bash
git clone https://github.com/katkhedepushpak/notes-app-frontend.git
git clone https://github.com/katkhedepushpak/notes-app-backend.git
