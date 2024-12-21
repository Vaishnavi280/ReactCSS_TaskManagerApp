Task Manager App

I developed a simple and interactive Task Manager App built with React and Vite. This application allows users to organize tasks by categories (Development, Testing, Deployment), mark tasks as completed, and shift tasks between categories with remarks as like JIRA/ServiceNow.

Features
Add Tasks: Create tasks and assign them to specific categories.
Shift Tasks: Move tasks between categories (Development, Testing, Deployment) with remarks.
Delete Tasks: Remove tasks from any category.
Dynamic Styling: Responsive design with CSS.
Real-Time Updates: Tasks update immediately without page refresh.
Tech Stack:
Frontend Framework: React (with Vite for fast builds)
Languages: JavaScript (ES6+), HTML, CSS
Styling: CSS Flexbox for responsive layouts
Project Setup:
Clone the Repository
https://github.com/your-username/taskmanagerapp.git
Navigate to the Project Directory
cd taskmanagerapp
Install Dependencies
npm install
Run the Development Server
npm run dev
Open in Browser
http://localhost:5173/

Folder Structure:
├── public/                # Static files
├── src/                   # Source code
│   ├── components/        # React components
│   ├── App.jsx            # Main App component
│   ├── main.jsx           # Entry point
│   ├── styles/            # CSS stylesheets
├── .gitignore             # Files to ignore in Git
├── package.json           # Project metadata
├── README.md              # Project documentation
└── vite.config.js         # Vite configuration

Future Enhancements:
Task Deadlines: Add due dates for tasks.
Drag and Drop: Enable drag-and-drop functionality for smoother task management.
Persistence: Save tasks using local storage or a database.
Authentication: Secure tasks with user accounts.

