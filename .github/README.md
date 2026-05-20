<!-- <p align="center">
  <img src="./frontend/src/assets/logo.png" alt="SchoolNotes Logo" height="100"/>
</p> -->

<h1 align="center">SchoolNotes</h1>
<p align="center">
  <strong>Simple note-taking platform for students.</strong>
</p>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-contributing">Contributing</a>
</p>

<p align="center">
  <!-- <img src="https://img.shields.io/github/v/release/DevHanza/SchoolNotes" alt="Version"/> -->
  <img src="https://img.shields.io/github/license/DevHanza/SchoolNotes" alt="License"/>
  <img src="https://img.shields.io/badge/node-18+-darkgreen.svg" alt="Node"/>
  <img src="https://img.shields.io/badge/Angular-18.x-red.svg" alt="Angular"/>

</p>

![Dashboard Preview](https://github.com/user-attachments/assets/466fca57-3a58-41c4-b645-ba91f6a5b81f)

## ✨ What is SchoolNotes?

**SchoolNotes** is a full-stack note-taking web application built for students to organize academic notes in one centralized dashboard.

The platform focuses on simplicity, fast note access, and category-based organization.

## 🎯 Features

- Create, edit, and delete notes
- Organize notes using categories
- Search and filter notes quickly
- Responsive dashboard layout
- RESTful CRUD API architecture
<!-- - Real-time UI updates after note operations -->

## 🔃 Quick Start

### 1. Install Requirements

- [Node.js](https://nodejs.org/en/download) _(v18.x+)_
- [MongoDB](https://www.mongodb.com/try/download/community)

### 2. Clone the Repository

```bash
git clone https://github.com/DevHanza/SchoolNotes.git

cd SchoolNotes
```

### 3. Install Dependencies

```bash
npm run install:everything
```

### 4. Configure Environment Variables

Create a .env file inside the `./server` folder:

```bash
MDB_URL = your_mongodb_connection_string
```

### 5. Start the Application

```bash
npm run start
```

## 💻 Tech Stack

### Frontend

- Angular v18
- Typescript

### Backend

- Node.js
- Express.js
- MongoDB
- [Mongoose](https://mongoosejs.com/)
- [cors](https://www.npmjs.com/package/cors)


## 🏭 Architecture Overview

```
Frontend (Angular)
        │
        ▼
REST API Calls
        │
        ▼
Express + Node.js Backend
        │
        ▼
MongoDB Database
```

## 🚀 Optimizations

- Structured reusable Angular components for easier scalability
- Improved note retrieval with category-based filtering
- Organized backend API using modular routes and controllers
- Enabled responsive UI updates without full page reloads

## 💪 Challenges Faced

<details> 
<summary>Keeping frontend note state synchronized after CRUD operations.</summary>

```
✅ Solved using Angular services and reactive UI updates.
```

</details>

<details> 
<summary>Designing a scalable API structure for note management.</summary>

```
✅ Solved by separating controllers, routes, and database models.
```

</details>

<details> <summary>Implementing fast note filtering and searching.</summary>

```
✅ Solved using frontend filtering logic and optimized state updates.
```

</details>

## 📝 Lessons Learned

Building SchoolNotes helped me strengthen my understanding of:

- Full-stack CRUD application development
- Angular component architecture and state handling
- RESTful API design using Express.js
- MongoDB schema modeling using Mongoose
- Structuring scalable frontend/backend folders

## 📍 Contributing

Pull requests are welcome.

For major changes, please open an issue first to discuss proposed improvements.

## 📄 License

This project is licensed under the **MIT License** – free for personal and commercial use.

See [LICENSE](./LICENSE) for details.
