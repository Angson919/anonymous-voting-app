# 🗳️ DeptVote

DeptVote is a secure, anonymous voting system designed for departmental elections. It prevents double-voting, maintains voter privacy, and publishes results after voting ends.

## 💡 Features

- User login via anonymous IDs
- One-vote-per-user enforcement
- Admin dashboard to add candidates and set voting period
- Real-time vote count (after deadline)
- Clean, simple UI

## 🛠 Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** FastAPI, SQLite (or JSON-based DB)
- **Auth:** Unique voter ID tokens

## 🚀 How to Run

1. Clone the repository
2. Run the FastAPI server: `uvicorn main:app --reload`
3. Visit the login page at `localhost:8000`

## 📸 Screenshot
<img width="1917" height="1079" alt="Screenshot 2025-04-23 004310" src="https://github.com/user-attachments/assets/cf460114-0708-4034-a910-59995d7053be" />



