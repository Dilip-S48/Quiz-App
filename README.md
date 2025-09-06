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
