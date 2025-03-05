# MERN Task Manager

## Project Overview
The **MERN Task Manager** is a full-stack web application built using the **MERN stack** (MongoDB, Express.js, React, Node.js). It allows users to manage tasks by creating, viewing, updating, and deleting them. Each task consists of a title, description, status, and due date. This project demonstrates **backend-frontend integration**, **RESTful API development**, **CRUD operations**, and **state management** in React.

## Features
- **Task Creation:** Users can add new tasks with a title, description, status, and due date.
- **Task Listing:** Displays all existing tasks in a structured view.
- **Task Editing:** Users can update task details.
- **Task Deletion:** Tasks can be removed from the system.
- **Status Management:** Task status can be set to "Pending", "In Progress", or "Completed".
- **Fully Responsive UI:** Styled using **Tailwind CSS**.
- **API Integration:** Uses **Axios** to communicate with the backend.
- **State Management:** Uses React hooks (**useState, useEffect**) for managing application state.
- **RESTful API:** Built using **Express.js** and **MongoDB** for efficient data management.
- **Deployment:** Backend hosted on **Render**, frontend on **Vercel**.

## Tech Stack
- **Frontend:** React.js, Axios, React Router, Tailwind CSS
- **Backend:** Node.js, Express.js, MongoDB, Mongoose, dotenv
- **Database:** MongoDB (Atlas or Local Instance)
- **Deployment:** Backend - Render, Frontend - Vercel

## Installation and Setup
### Prerequisites
Ensure you have the following installed:
- **Node.js** (v14+ recommended)
- **MongoDB** (local or cloud via MongoDB Atlas)
- **Git**

### Step 1: Clone the Repository
```sh
git clone https://github.com/kaidavi/PLP-Full-Stack-Development-MERN-Week-4.git
cd mern-task-manager
```

### Step 2: Backend Setup
```sh
cd backend
npm install
```

#### Environment Variables
Create a `.env` file in the `backend` directory and add:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

#### Start Backend Server
```sh
npm run dev
```
By default, the backend will run on `http://localhost:5000`

### Step 3: Frontend Setup
```sh
cd frontend
npm install
```

#### Start Frontend Server
```sh
npm start
```
By default, the frontend will run on `http://localhost:3000`

## API Endpoints
| Method | Endpoint         | Description            |
|--------|-----------------|------------------------|
| GET    | /api/tasks      | Get all tasks         |
| POST   | /api/tasks      | Create a new task     |
| GET    | /api/tasks/:id  | Get a single task     |
| PUT    | /api/tasks/:id  | Update a task by ID   |
| DELETE | /api/tasks/:id  | Delete a task by ID   |

## Folder Structure
```plaintext
mern-task-manager/
│-- backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── config/
│   ├── server.js
│   ├── .env
│-- frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   ├── index.js
│-- README.md
│-- package.json
```

## Deployment
### Deploy Backend to Render
1. Push your backend code to GitHub.
2. Create a new service on [Render](https://render.com/).
3. Connect your repository and deploy.
4. Set environment variables in Render settings.

### Deploy Frontend to Vercel
1. Push your frontend code to GitHub.
2. Create a new project on [Vercel](https://vercel.com/).
3. Connect your repository and deploy.
4. Update API URLs in the frontend to use the deployed backend.

## Usage Guide
1. Open the application.
2. Add new tasks by filling out the form.
3. View all tasks in the task list.
4. Click on a task to edit or delete it.
5. Update the task status as needed.

## Testing
### API Testing with Postman
1. Start the backend server.
2. Open **Postman** and test the API endpoints listed above.

### UI Testing
1. Start the frontend server.
2. Open `http://localhost:3000` in your browser.
3. Check if tasks can be added, edited, and deleted correctly.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License
This project is open-source and available under the **MIT License**.

---

### Author
Developed by **[David Kai]** -
Check deployed project at https://plp-full-stack-development-mern-week-4.vercel.app/

