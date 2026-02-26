# 📚 BookBinder
A Smart Full-Stack Reading Tracker with AI Assistant
Built using **Node.js, Express, MongoDB, EJS, and Ollama**
------------------------------------------------------------------------------------------------

## Project Overview

BookBinder is a modern full-stack web application that allows users to:

* Track books they want to read
* Monitor reading progress
* Rate books visually
* View detailed book information
* Automatically fetch book covers
* Get AI-powered book recommendations using Ollama

This project demonstrates complete CRUD functionality, database integration, API usage, authentication, and AI model integration.

------------------------------------------------------------------------------------------------

## Problem Statement

Readers often struggle to:

* Organize their reading list efficiently
* Track progress visually
* Rate books in a structured way
* Get intelligent recommendations

BookBinder solves these problems using a structured digital system enhanced with AI.

------------------------------------------------------------------------------------------------

## Tech Stack

### Frontend

* EJS (Templating Engine)
* HTML5
* CSS3
* JavaScript

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### AI Integration

* Ollama (Local LLM)
* Llama3 Model

### External API

* Google Books API (Automatic cover fetching)

------------------------------------------------------------------------------------------------

## Features

### Core Features

* User Authentication (Signup/Login/Logout)
* Add, Edit, Delete Books
* Categorized Book View:
  * To Read
  * Reading
  * Finished
* Reading Progress Tracking
* Visual Star Rating System

### UI/UX Features

* StoryGraph-inspired cover-first grid layout
* Hover overlay with quick actions
* Responsive design
* Custom logo & typography
* Interactive homepage carousel
* Modern Book Detail page with:
  * Large cover display
  * Progress bar
  * Rating display
  * Notes section

### AI Assistant

* Integrated chatbot powered by Ollama
* Provides book recommendations
* Runs locally (no external AI API required)
* Example prompt:
  > “Suggest 3 Indian fiction books and why I might like them.”

------------------------------------------------------------------------------------------------

## CRUD Implementation

| Operation | Description                  |
| --------- | ---------------------------- |
| Create    | Add new book                 |
| Read      | View categorized books       |
| Update    | Edit rating, progress, notes |
| Delete    | Remove book                  |

------------------------------------------------------------------------------------------------

## Project Structure

book-binder/
│
├── config/
├── models/
├── routes/
├── views/
│   ├── books/
│   ├── auth/
│   ├── partials/
│   └── chat/
├── public/
│   └── css/
├── server.js
├── package.json
└── README.md
```

------------------------------------------------------------------------------------------------

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/YOUR_USERNAME/bookbinder.git
cd bookbinder
```

### 2️⃣ Install Dependencies

```
npm install
```

### 3️⃣ Start MongoDB

Ensure MongoDB is running locally.

### 4️⃣ Start Ollama

Make sure Ollama is installed.

Run:

```
ollama run llama3
```

Or ensure Ollama server is running:

```
ollama serve
```

(Default Port: 11434)

### 5️⃣ Start the Application

```
node server.js
```

Open in browser:

```
http://localhost:3000
```

---

## 🧠 AI Integration Details

The chatbot communicates with the Ollama local server:

* Endpoint: `http://localhost:11434`
* Model: `llama3`
* Responses are dynamically rendered on the chat page.

The AI assistant enhances user experience by providing contextual reading recommendations.

------------------------------------------------------------------------------------------------

## 📊 Future Improvements

* Reading Analytics Dashboard
* Search & Filtering System
* Dark Mode
* Cloud Deployment (Render / Railway)
* Personalized AI recommendations based on reading history
* Save recommended books directly to library

------------------------------------------------------------------------------------------------

## 🎓 Learning Outcomes

Through this project, I gained experience in:

* Full-stack web development
* RESTful routing
* MongoDB schema design
* API integration
* Authentication systems
* AI model integration (LLM via Ollama)
* UI/UX design improvements
* Debugging and performance optimization

------------------------------------------------------------------------------------------------

## 📸 Screenshots

![Home Page](<img width="1824" height="863" alt="Screenshot 2026-02-26 222107" src="https://github.com/user-attachments/assets/1b0e692b-08cb-41ba-a1cd-fc11988c665b" />)
![Library](<img width="1666" height="866" alt="Screenshot 2026-02-26 222336" src="https://github.com/user-attachments/assets/83121f53-13da-42d3-9d93-bc37856bfc5d" />)
![Book Detail](<img width="1821" height="860" alt="Screenshot 2026-02-26 222446" src="https://github.com/user-attachments/assets/5fe9a93d-40fe-4ff7-b540-2a498cd7f429" />)
![Chatbot](<img width="1835" height="848" alt="Screenshot 2026-02-26 223602" src="https://github.com/user-attachments/assets/93296489-4577-45f2-8e94-20c9b25a40f7" />)
```

------------------------------------------------------------------------------------------------

## 🏁 Conclusion

BookBinder demonstrates the integration of:

* Backend logic
* Database management
* Frontend UI design
* External API consumption
* AI model integration

It is a scalable full-stack application suitable for further enhancements and real-world deployment.

------------------------------------------------------------------------------------------------
