# 🤖 Chatbot 

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=6C5CE7&center=true&width=700&lines=🤖+AI+Chatbot+System;Smart+Conversations+in+Real-Time;Built+with+Flask+%26+Gemini+API" alt="Typing animation" />
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Flask-2.0+-green.svg?style=for-the-badge&logo=flask&logoColor=white">
  <img src="https://img.shields.io/badge/Gemini%20API-AI-orange.svg?style=for-the-badge">
  <img src="https://img.shields.io/badge/SQLite-Database-lightgrey.svg?style=for-the-badge&logo=sqlite">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
</p>

---

## 🏷️ Logo

<p align="center">
  <img src="static/images/logo.png" alt="Chatbot Logo" width="300">
</p>

---

## 🚀 About the Project

This **AI Chatbot** is a full-stack conversational system built using **Python (Flask)** and **Google Gemini API**.

It enables users to interact with an intelligent assistant in real-time, featuring a **modern UI**, **instant responses**, and **chat history storage** using a database.

---

## 🎯 Who is This Project For?

| Audience | Why |
|----------|-----|
| 👨‍🎓 Students | Learn AI + Web + Database integration |
| 🧑‍💻 Beginners | Understand Flask APIs and chatbot logic |
| 🤖 AI Enthusiasts | Explore Gemini API |
| 📚 Educators | Demonstrate chatbot systems |

---

## ✨ Features

### 👤 User Features

| Feature | Description |
|---------|-------------|
| 💬 Chat with AI | Real-time intelligent responses |
| 🎨 Beautiful UI | Gradient-based modern chat design |
| ⚡ Instant Replies | Fast response using Gemini |
| 🎯 Text Highlighting | Important parts highlighted |
| ⌨️ Enter to Send | Smooth interaction |

---

### ⚙️ System Features

| Feature | Description |
|---------|-------------|
| 🧠 Gemini API Integration | AI-powered responses |
| 💾 Chat Storage | Stores conversations in DB |
| 🔄 Session Memory | Maintains chat context |
| ⚡ Flask API Backend | Handles requests |
| 🛡️ Error Handling | Handles failures gracefully |

---

## 🧱 Built With

### 🎨 Frontend
- HTML5  
- CSS3  
- JavaScript  

### ⚙️ Backend
- Python 3.8+  
- Flask  
- Google Generative AI  

### 🗄️ Database
- SQLite (`chatbot.db`)

---

## 🖼️ Screenshots

### 💬 Chat Interface
![Chat UI](Screenshots/chat_ui.png)

---

## ⏱️ Chat Flow

| Step | Action |
|------|--------|
| 1 | User sends message |
| 2 | Flask receives request |
| 3 | Gemini processes input |
| 4 | AI generates response |
| 5 | Chat stored in database |
| 6 | Response shown to user |

---

## 📂 Database Schema
sql
CREATE TABLE chats (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    user_message TEXT,
    bot_response TEXT,
    timestamp DATETIME DEFAULT CURRENT_TIMESTAMP
);
## 🔌 API Endpoints

### 📄 Page Routes

| Route | Page |
|-------|------|
| `/`   | Chat Interface |

---

### ⚙️ API Routes

| Route  | Method | Purpose |
|--------|--------|---------|
| `/chat` | POST   | Send message & get response |

---

## 🔧 Installation

### 📌 Prerequisites

- Python 3.8+
- Gemini API Key

---
### 📦 Step 1: Install Dependencies
pip install flask google-generativeai

---

### 🔑 Step 2: Add API Key
import os  
GOOGLE_API_KEY = os.getenv("GOOGLE_API_KEY")

---

### ▶️ Step 3: Run App
python app.py

---

### 🌐 Step 4: Open Browser
http://127.0.0.1:5000

---

## 🧭 Usage Guide
Step 1: Open chatbot  
↓  
Step 2: Type message  
↓  
Step 3: Click Send / Press Enter  
↓  
Step 4: Get AI response  
↓  
Step 5: Chat saved in database  

---

## 🏗️ Architecture
User → Frontend → Flask API → Gemini API → Database → Response

---

## 🗂️ Project Structure
chatbot/  
├── app.py  
├── templates/  
│   └── index.html  
├── static/  
├── chatbot.db  
├── Screenshots/  
└── README.md  

---

## 💡 Key Highlights
🤖 Real-time AI chatbot  
💾 Stores chat history  
🎨 Clean UI design  
⚡ Fast responses  

---

## 🔐 Security Features
Feature | Description  
--------|------------  
🔒 API Key Protection | Use environment variables  
🛡️ Input Validation | Prevent empty input  
⚠️ Error Handling | Handles API limits  

---

## 📊 Project Metrics
Metric | Value  
-------|------  
API Endpoints | 1  
Database Tables | 1  
Pages | 1  
Response Time | ~1–2 sec  

---

## 👤 Developer
Name | Role  
-----|------  
Chinthapatla Sudheer| 🤖 Developer  













