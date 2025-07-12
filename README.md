 *  Made with ❤️ by Himanshu Ojha  *


# 🧠 Task Manager Backend

This is the **backend** of the Task Manager web application — a powerful tool to manage tasks, assign team members, track progress, and export reports. Built using Node.js, Express, and MongoDB.

---

## 🚀 Features

- User authentication (Register/Login)
- Role-based access (Admin/User)
- Create, update, delete tasks
- Assign tasks to multiple users
- Attach files, manage todo checklists
- Track task progress
- Export task/user reports in Excel
- Secure REST API with JWT

---

## 🛠️ Tech Stack

- **Node.js + Express**
- **MongoDB + Mongoose**
- **JWT Authentication**
- **Multer** for file upload
- **ExcelJS** for report export
- **dotenv** for environment management

---

## 📁 Folder Structure

task-manager-backend/
│
├── controllers/         # Route logic
├── models/              # Mongoose schemas
├── routes/              # API routes
├── middlewares/         # Auth & error middlewares
├── utils/               # Helper functions
├── uploads/             # Uploaded files
├── .env                 # Environment variables (Not committed)
├── .gitignore
├── server.js            # Entry point

---

## ⚙️ Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/himanshuojha2000/task-manager-backend.git
   cd task-manager-backend

2. Install Dependencies
   ```bash
   npm install

3.  Add.env file
    PORT=8000
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret

4. Run the server
   ```bash
    npm start



## API ENDPOINTS

*Method          Endpoint                      Description*
POST            /api/auth/register            Register user
POST            /api/auth/login               Login user
GET             /api/users                    Get all users (admin)
POST            /api/tasks                    Create new task
GET             /api/tasks                    Get all tasks
GET             /api/tasks/:id                Get single task by ID
PUT             /api/tasks/:id                Update task
DELETE          /api/tasks/:id                Delete task
GET             /api/reports/exports/tasks    Export all tasks (Excel)
GET             /api/reports/exports/users    Export user reports (Excel)


🧪 Testing

You can use Postman or Thunder Client to test the APIs locally.


🤝 Contributing

Pull requests and suggestions are welcome!
To contribute:
	1.	Fork the repo
	2.	Create a branch: git checkout -b feature/your-feature
	3.	Commit: git commit -m 'Add your feature'
	4.	Push: git push origin feature/your-feature
	5.	Create a Pull Request

 ---

Let me know when you're ready for the **frontend `README.md`**, or want a short `env.example` too.
