# Student-Database-Managment-System
#  Student Database Management System (React)

##  Project Overview

This is a **Student Database Management System** built using **React.js**.
The project is created for **practice and learning purposes**.
It allows users to manage student records efficiently with full **CRUD functionality**.

---

##  Features

The application includes the following features:

*  **Add Student** (Insert student data using form)
*  **View Students** (Display student records)
*  **Edit Student Details**
*  **Update Student Information**
*  **Delete Student Record**
*  **Search Student by Name**
*  **Search Student by Mobile Number**

---

##  Technologies Used

* **React.js** – Frontend UI
* **JSON Server** – Backend (Mock API)
* **db.json** – For storing student data
* **HTML, CSS, JavaScript**

---

##  Database Details

Student data is stored using **db.json** file with **JSON Server**.

###  API Endpoint

```
http://localhost:3000/students
```

This API is used to:

* Fetch student data
* Add new students
* Update existing student records
* Delete student entries
* Search students by name or number

---

##  How to Run the Project

### 1️⃣ Install Dependencies

```
npm install
```

### 2️⃣ Start React Application

```
npm run dev
```

### 3️⃣ Start JSON Server

```
npx json-server --watch db.json --port 3000
```

---

## 📄 Sample Student Data Structure

```
{
  "id": 1,
  "name": "Student Name",
  "mobile": "9876543210",
  "email": "student@example.com",
  "course": "React JS"
}
```

---

##  Purpose of the Project

* To understand **React CRUD operations**
* To practice **API integration**
* To learn **state management & form handling**
* To work with **JSON Server as backend**

---

## 👩‍💻 Author

**Ankita Bobde**
React Practice Project 

---

##  Note

This project is made for **learning and practice purpose only**.

---

✨ *Feel free to improve and customize this project further!*
