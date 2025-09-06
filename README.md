# 📝 Quiz App (Flask + SQLite)

A simple yet powerful **Quiz Application** built with **Flask**, **SQLite**, and **Bootstrap**.  
Supports **user registration, quiz management, quiz-taking with timer, results tracking, and admin controls**.  

---

## 🚀 Features
### 👤 Users
- Register and log in securely (passwords hashed).
- Take quizzes within a set duration.
- View personal results with detailed answers (correct vs. chosen).
- See percentage scores.

### 🛠 Admin
- Manage quizzes (create, edit, delete).
- Add/edit/delete questions.
- Edit quiz title and duration.
- Cascade delete quizzes and related results/questions.
- Manage users (list, delete users).
- View statistics (total users, quizzes, attempts).

### 📊 Results
- Each attempt is stored with:
  - Score, total, and percentage.
  - User’s selected answers.
  - Detailed review page showing all options, ✅ correct answer, and 📝 user’s choice.

---

## 🗂 Project Structure
quiz_app/
│── app.py # Main Flask app
│── quiz.db # SQLite database (auto-created)
│── templates/ # HTML templates
│ ├── base.html
│ ├── index.html
│ ├── login.html
│ ├── register.html
│ ├── add_quiz.html
│ ├── manage_quiz.html
│ ├── edit_question.html
│ ├── quiz.html
│ ├── result.html
│ ├── my_results.html
│ ├── view_result.html
│ └── admin_users.html
│── static/ # CSS/JS (Bootstrap loaded via CDN)
│── README.md # Project documentation

---

## ⚙️ Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/yourusername/quiz-app.git
   cd quiz-app
2. Create virtual environment
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
3. Install dependencies
   pip install flask flask_sqlalchemy flask_login werkzeug
4. Run the app
   python app.py
5. Open in browser:
   http://127.0.0.1:5000/
🔑 Default Admin

When the app starts, it ensures an admin account exists:

Username: admin

Password: admin

⚠️ For security, change the password after first login.

🧑‍💻 Tech Stack

Backend: Flask (Python)

Database: SQLite (via SQLAlchemy ORM)

Frontend: HTML + Bootstrap

Auth: Flask-Login

📸 Screenshots (Optional)

Add screenshots here if you want.

🛡 License

This project is licensed under the MIT License – feel free to use and modify.
