# PantherBot: AI-Powered Academic Program Chatbot

## 📌 Project Overview
**PantherBot** is an AI-driven chatbot built to assist students in exploring **undergraduate and graduate programs** at Georgia State University (GSU).  
By integrating **OpenAI’s LLM** with structured program datasets and real-time search, PantherBot delivers **quick, accurate, and conversational guidance** to help students find the right program for their interests.  

This project was developed as part of **MSA 8700**, focusing on designing and deploying a **practical AI business solution** using large language models (LLMs).

---

## 🎯 Business Problem
Students often struggle to identify the right academic program due to **fragmented, lengthy, and difficult-to-navigate information** across university websites.  
This leads to confusion, delays, and poor decision-making.  

**PantherBot addresses this by:**  
- Providing a **conversational interface** to explore program details  
- Summarizing tuition, faculty, curriculum, and outcomes in real time  
- Offering **personalized recommendations** based on queries  
- Falling back to **Google Search** when internal datasets are insufficient  

---

## 🏗️ Solution Architecture
- **Frontend:** Streamlit (responsive, mobile-friendly chat interface)  
- **AI Backend:** GPT-4 Turbo via OpenAI API with prompt chaining + multi-turn memory  
- **Datasets:** Two structured Excel files (undergraduate + graduate program listings)  
- **External Search:** Google (via Serper.dev API) for real-time data gaps  
- **Deployment:** Streamlit Community Cloud (public access, no setup required)  
- **Future-Ready:** Offline mode planned with **local Ollama integration**  

---

## ✨ Key Features
- 🔍 Intelligent program search across undergraduate & graduate offerings  
- 📊 Real-time details: tuition, faculty, outcomes, curriculum  
- 🌐 Google Search fallback for missing program data  
- 💬 Multi-turn conversation memory for smooth dialogue flow  
- 🎨 Clean UI with avatars, animations, and feedback form  
- 📱 Mobile-friendly design  
- 🔒 Future-ready offline chatbot (Ollama)  

---

## 🚀 Live Application
👉 [**Click Here to Try PantherBot**](#)  

Accessible to **students, faculty, and instructors** for demo, feedback, and evaluation.  

---

## ⚙️ Setup Instructions

Clone the repository:
```bash
git clone https://github.com/Harshalk2002/Chat_bot.git
cd Chat_bot
