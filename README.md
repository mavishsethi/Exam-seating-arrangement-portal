# 🎓 Exam Seating Arrangement System (MERN Stack)

A full-stack web application for managing student exam seating arrangements, teacher duties, and administrative tasks in an educational institution.

---

## 🔧 Tech Stack

- **Frontend**: React.js , Axios
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB (Mongoose ODM)  
- **Auth**: JWT, bcrypt  
- **File Uploads**: Multer

---



## 📁 Project Structure

```bash
client/          # React frontend
server/          # Express backend
uploads/         # Uploaded profile photos and files
.env             # Environment variables (not pushed)
```

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/exam-seating-app.git
cd exam-seating-app
```

### 2. Setup Server
```bash
cd server
npm install
touch .env      # Add JWT_SECRET, DB_URI, etc.
npm start
```

### 3. Setup Client
```bash
cd client
npm install
npm run dev
```
