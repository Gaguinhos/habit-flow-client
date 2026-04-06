# 📱 Habit-Flow Client

## 📌 Overview

The **Habit-Flow-client** is the front-end application responsible for user interaction in the habit tracking system.

---

## 🧠 Architecture (MVP)

![System Architecture](https://github.com/user-attachments/assets/e2a6231a-6a18-4f00-a763-a7f23f66d4c9)

### 🔎 Explanation

- **Client (Front-End)** → User interface  
- **Server (Back-End)** → Processes data  
- **Database** → Stores information  

👉 Flow: Client → Server → Database

---

## 🎯 Purpose

- Create habits  
- Track progress  
- Edit habits  
- Delete habits  
- View statistics  

---

## 📲 Interface

![App Interface](https://github.com/user-attachments/assets/26341304-73ec-4a62-a1c1-c59904358c3b)

---

## 📲 Features

- Create Habit  
- List Habits  
- Mark as Completed  
- Edit Habit  
- Delete Habit  
- View Statistics  

---

## 🔗 Communication

The client communicates with the server using HTTP requests:

- GET → Fetch habits  
- POST → Create habit  
- PUT/PATCH → Update habit  
- DELETE → Delete habit  

---

## 🗂️ Project Structure
```
Habit-Flow-client/
│
├── src/
│   ├── components/
│   ├── screens/
│   ├── services/ (API)
│   ├── hooks/
│   ├── styles/
│   └── utils/
│
├── assets/
├── package.json
└── README.md
```
---

## 🚀 Technologies

- React / React Native  
- TypeScript  
- Axios  
- Expo  

---

## 🔐 Security

- JWT Authentication  
- Protected routes  
- Data validation  

---

## ✅ Conclusion

This is the user interface layer of the system.
