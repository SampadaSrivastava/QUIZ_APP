# Quiz App - MERN Stack

A full-stack Quiz Application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js). The platform allows admins to create and manage quizzes while users can participate in quizzes, track scores, and view performance analytics.

---

## 🚀 Features

### Admin Features
- Create, edit, and delete quizzes
- Add multiple-choice questions and answers
- Manage quiz content dynamically
- View student performance analytics
- Monitor quiz statistics and leaderboard

### User Features
- User authentication (Register/Login)
- Attempt interactive quizzes
- Instant score calculation
- Real-time leaderboard updates
- Track quiz history and progress
- Responsive UI for desktop and mobile devices

---

## 🛠 Tech Stack

### Frontend
- React.js
- React Router DOM
- Axios
- Material-UI
- Chart.js

### Backend
- Node.js
- Express.js
- JWT Authentication
- Mongoose

### Database
- MongoDB Atlas

---

## 📂 Project Structure

```bash
quiz-app/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   └── server.js
│
└── README.md
🔐 Authentication
JWT-based authentication system
Protected admin routes
Secure password hashing using bcrypt
Role-based access control (Admin/User)
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/Quiz.git
cd Quiz
2️⃣ Backend Setup
cd backend
npm install

Create a .env file inside backend folder:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000

Run backend server:

npm start
3️⃣ Frontend Setup
cd frontend
npm install
npm run dev
📡 API Endpoints
Method	Endpoint	Description
POST	/api/auth/register	Register User
POST	/api/auth/login	Login User
GET	/api/quiz	Get All Quizzes
POST	/api/admin/quiz	Create Quiz
PUT	/api/admin/quiz/:id	Update Quiz
DELETE	/api/admin/quiz/:id	Delete Quiz
📊 Key Functionalities
Dynamic quiz generation
Real-time score tracking
Leaderboard system
Analytics dashboard
RESTful API integration
Responsive and modern UI
🧠 Challenges Faced

One major challenge was implementing real-time leaderboard updates and synchronized quiz timers. This was solved by optimizing frontend state management and improving backend API response handling.

📈 Future Improvements
Add Socket.IO for live quiz battles
Implement dark mode
Add AI-generated quiz suggestions
Add email notifications
Deploy using Docker and CI/CD pipelines
👨‍💻 Author

Sampada Srivastava

📜 License

This project is developed for educational and portfolio purposes.
